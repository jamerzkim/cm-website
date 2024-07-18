<script>
  import "../app.css";
  import Navbar from './components/Navbar.svelte';
</script>

<Navbar />
<!-- think about adding a header, so that the header applies to all pages. but depending on the page name the header will change -->
<!-- but there will be a default header. so like lets say i go to ./team, the header will use Team in the title. that way it can flow with the navbar -->
<slot />

<style>
  /* :global(body) {
    font-family: 'Montserrat', sans-serif;
  } */
</style>