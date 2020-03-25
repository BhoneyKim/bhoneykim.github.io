<script>
import SymbolicContents from './Contents/SymbolicContents.svelte';
import DetailContents from './Contents/DetailContents.svelte';

</script>

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

</style>

<div class="content-container">
    <SymbolicContents/>

    <DetailContents/>
</div>