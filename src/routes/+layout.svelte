<script>
  import "../app.css";
  import Header from "$lib/components/Header.svelte";
  import HeaderPost from "$lib/components/HeaderPost.svelte";
  import { page } from '$app/stores'; 

  console.log($page.url.pathname)
</script>

<svelte:head>
  <title>Rad Institute</title>
</svelte:head>

{#if $page.url.pathname === "/"}
  <Header />
{:else}
  <HeaderPost />
{/if}

<slot />
