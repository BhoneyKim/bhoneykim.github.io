<script>

    let src = "./SVG/Imagineer.svg";
</script>


<style>

.symbolic-text{
    /* font-size: 15rem; */
    /* writing-mode: vertical-rl; */
    /* padding: 5%; */
    
    max-width: 100%;
    max-height: 100%;

    object-fit: contain;

    margin-left: 23.95%;
    margin-right: 14.6%;
    margin-top: 30%;
    margin-bottom: 30%;
}
.symbolic-content-wrapper{
    order: 1;
    align-content: center;
    justify-content: center;
}
.content-col{
    background-color: black;
    flex: 1;
    max-height: 100%;
    max-width: 100%;
}
/* .text-rotate-container{
    position: absolute;
    background-color: #abcdef;
    transform-origin: 50% 50%;
    transform: rotate(0deg);
} */

</style>

<div class="content-col symbolic-content-wrapper">
        <img class="symbolic-text" {src} alt="symbolicImage">
</div>

<!-- 
<div class="content-col symbolic-content">
    <div class="text-rotate-container">
        <h1 class="symbolic-text">
            Imagineer
        </h1>
    </div>
</div>
 -->
