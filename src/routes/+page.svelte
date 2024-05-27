<script>
  import Header from "$lib/Header.svelte";
  import Nav from "$lib/Nav.svelte";
</script>

<Header />

<Nav />

<main>
  <p>32 november 2007 20:65 am no idea where</p>

  <img src="hanny-naibaho.jpg" alt="" />
</main>

<footer>
  <p>&copy; Craighead Diocesan School 2024</p>
</footer>

<style>
  /* h2 {
    background-color: #f6e9ff;
  } */

  main {
    background-color: #f6e9ff;
    display: grid;
    grid:
      ".  I" 25vh
      "H   I" 25vh
      "P   I" 25vh
      "N   I" 25vh
      "F   F" 25vh
      / 1fr 1fr;
  }

  footer {
    background-color: #f6e9ff;
    grid-area: F;
  }
</style>
