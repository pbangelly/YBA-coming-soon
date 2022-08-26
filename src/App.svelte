<script>
  import YBA from "./assets/your-bad-angel-logo.png";
  import Counter from "./lib/index.svelte";
  // import Footer from "./comp/footer.svelte";
</script>

<main class="container mx-auto">
  <div>
    <!-- <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite Logo" />
    </a> -->
    <a href="/" target="_blank">
      <img
        src={YBA}
        class="your bad angel womens clothing logo"
        alt="Your Bad Angel Logo"
      />
    </a>
  </div>
  <h1>Your Bad Angel</h1>

  <div class="card">
    <Counter />
  </div>

  <p class="read-the-docs">yourbadangel.com</p>

  <!-- <Footer /> -->
</main>

<style>
  .logo {
    height: 15em;
    padding: 1.5em;
    will-change: filter;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  /* .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  } */
  .read-the-docs {
    color: rgb(75, 74, 74);
    text-transform: uppercase;
  }
  h1 {
    color: #ce0014;
    font-size: 7em;
    font-family: "Tangerine", serif;
    text-shadow: 4px 4px 4px #aaa;
    text-transform: capitalize;
  }
</style>
