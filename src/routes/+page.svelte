<script>
  import Header from "$lib/Header.svelte";
  import Nav from "$lib/Nav.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<Header />

<Nav />

<main>
  <p>32 november 2007 20:65 am no idea where</p>

  <img src="samuel-regan-asante.jpg" alt="" />
</main>

<Footer />

<style>
  /* h2 {
    background-color: #f6e9ff;
  } */
  /* header {
    grid-area: H;
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

  p {
    grid-area: P;
    font-family: "KoHo", sans-serif;
    font-weight: 500;
    color: #9468cf;
    font-size: 3rem;
  }

  img {
    grid-area: I;
  }

  /* footer {
    background-color: #f6e9ff;
    grid-area: F;
  } */
</style>
