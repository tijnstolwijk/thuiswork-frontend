<!-- Eerst standaard svelte layout maken
    script
    html
    css
!-->

<script lang="ts">
  import Articlebox from '../components/articlebox.svelte'
</script>

<svelte:head>
    <title> SvelteKit testing environment </title>
</svelte:head>

<h1>
Svelte test environment
</h1>

<Articlebox  />


<style>
h1 {
color: #d08770;
}
</style>
