<script>
  import Footer from "$lib/Footer.svelte";
</script>

<header>
  <h1>sunburst</h1>
  <h1>festival</h1>
</header>

<main>
  <p>32 november 2007</p>
  <p>20:65 am</p>
  <p>no idea where</p>
</main>
<img src="samuel-regan-asante.jpg" alt="" />

<nav>
  <a href="/">home</a>
  <a href="/general">general</a>
  <a href="/acts">acts</a>
  <a href="/accommodation">accommodation</a>
</nav>
<Footer />

<style>
  h1 {
    text-transform: uppercase;
    font-family: "Kufam", sans-serif;
    color: #9468cf;
    font-size: 5rem;
    font-weight: 700;
    background-color: #f6e9ff;
    grid-area: H;
  }

  main {
    background-color: #f6e9ff;
    width: 720px;
    /* display: flex; */
  }

  p {
    grid-area: P;
    font-family: "KoHo", sans-serif;
    font-weight: 500;
    color: #9468cf;
    font-size: 3rem;
    margin: 10px;
    text-align: left;
  }

  nav {
    grid-area: N;
  }
  a {
    color: #f6e9ff;
    background-color: #9468cf;
    font-size: 1.65rem;
    font-family: "KoHo", sans-serif;
    font-weight: 500;
    padding: 10px;
    margin: 10px;
  }

  img {
    grid-area: I;
    width: 720px;
  }
</style>
