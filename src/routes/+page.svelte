<script>
  import Banner from "$lib/Banner.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<Banner />
<main>
  <div class="content">
    <header>
      <div class="header">
        <h1>sunburst festival</h1>
      </div>
      <div class="text">
        <h2>32 november 2007</h2>
        <h2>20:65 am</h2>
        <h2>no idea where</h2>
      </div>
    </header>

    <nav>
      <div class="nav">
        <div class="right">
          <a href="/">home</a>
        </div>
        <div class="left">
          <a href="/general">general</a>
        </div>
        <div class="left">
          <a href="/acts">acts</a>
        </div>
        <div class="left">
          <a href="/accommodation">accommodation</a>
        </div>
      </div>
    </nav>
  </div>

  <img
    src="samuel-regan-asante copy.jpg"
    alt="a festival crowd surrounded by purple light and confetti"
    title="Samuel Regan Asante"
  />
</main>
<Footer />

<style>
  main {
    background-color: #f6e9ff;
    width: 720px;
    display: flex;
  }

  h1 {
    text-transform: uppercase;
    font-family: "Kufam", sans-serif;
    color: #9468cf;
    font-size: 6rem;
    font-weight: 700;
    background-color: #f6e9ff;
    margin: 30px 0px;
  }

  h2 {
    font-family: "KoHo", sans-serif;
    font-weight: 500;
    color: #9468cf;
    font-size: 2.7rem;
    margin: -30px 10px;
    text-align: left;
  }
  .header {
    background-color: #f6e9ff;
    padding: 100px 30px 1px;
  }
  .text {
    background-color: #f6e9ff;
    padding: 25px 30px 50px;
  }
  .nav {
    display: flex;
    flex-direction: row;
    background-color: #f6e9ff;
    padding: 20px 0px 20px 30px;
  }
  a {
    color: #f6e9ff;
    background-color: #9468cf;
    font-size: 1.65rem;
    font-family: "KoHo", sans-serif;
    font-weight: 500;
    padding: 10px 20px;
    margin: 10px;
    transition: 0.4s;
  }

  a:hover {
    background-color: #5c3c9c;
    transition: 0.4s;
  }

  img {
    width: 730px;
  }

  .content {
    width: 730px;
    margin-right: 71px;
  }
</style>
