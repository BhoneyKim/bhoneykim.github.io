<script>
import SymbolicContents from './Contents/SymbolicContents.svelte';
import DetailContents from './Contents/DetailContents.svelte';

let y_scroll, scrollConstant_d, scrollConstant_s;
let SymbolicContent_height, DetailContent_height;
var height;
function getHeights(){
    SymbolicContent_height = document.getElementById("SymbolicContents_wrap").firstChild.offsetHeight;
    DetailContent_height = document.getElementById("DetailContents_wrap").childNodes[1].offsetHeight;
    
    console.log(SymbolicContent_height + " & " + DetailContent_height);
    
    // height = document.getElementById("Contents_wrap").offsetHeight;
    height = SymbolicContent_height>DetailContent_height?SymbolicContent_height:DetailContent_height;
    scrollConstant_d = DetailContent_height / height;
    scrollConstant_s = SymbolicContent_height / height;
    console.log(height);
}

window.addEventListener("DOMContentLoaded",function(){
    getHeights();
});

window.addEventListener('scroll', function() {
    console.log(y_scroll);
});

</script>

<svelte:window bind:scrollY={y_scroll}/>

<style>

.content-container{
    display: flex;
    flex-direction: row;
}

@media screen and (max-width:600px){
    .content-container{
        display: flex;
        flex-direction: column;
    }
}

.content-col{
    background-color: black;
    flex: 1;
    max-height: 100%;
    max-width: 100%;
}

#SymbolicContents_wrap{
    order: 1;
}
#DetailContents_wrap{
    order: 2;
}

</style>

<div class="content-container" id="Contents_wrap">
    <span class="content-col" id="SymbolicContents_wrap" style="transform: translate(0,{(-y_scroll * scrollConstant_s)}px"><SymbolicContents/></span>
    <span class="content-col" id="DetailContents_wrap" style="transform: translate(0,{(-y_scroll * scrollConstant_d)}px"><DetailContents/></span>    
</div>