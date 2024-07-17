<script>
  import "../app.css";
  import Navbar from './components/Navbar.svelte';
</script>

<Navbar />
<slot />

<style>
  /* :global(body) {
    font-family: 'Montserrat', sans-serif;
  } */
</style>