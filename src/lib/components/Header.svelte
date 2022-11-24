<script>
  import Nav from "./Nav.svelte";
  import Logo from "./Logo.svelte";
</script>

<header>
  <a href="/" class="logo"><h1>Rad Institute</h1></a>
  <Nav />
</header>

<style>
  .logo {
    width: 100%;
    font-size: 6vw;
    font-weight: normal;
    font-family: var(--special-font);
    top: var(--space-large);
  }

  header {
    position: static;
  }
</style>
