<script>
import SymbolicContents from './Contents/SymbolicContents.svelte';
import DetailContents from './Contents/DetailContents.svelte';

</script>

<style>

.content-container{
    display: flex;
    flex-direction: row;
}
</style>

<div class="content-container">
    <SymbolicContents/>

    <DetailContents/>
</div>