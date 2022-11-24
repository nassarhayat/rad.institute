<script>
  import Newsletter from "$lib/components/Newsletter.svelte";
  import HeaderSmall from "../../lib/components/HeaderSmall.svelte";
  import PageTitle from "../../lib/components/pageTitle.svelte";
</script>

<HeaderSmall />
<PageTitle>Fellowships</PageTitle>
<img src="/imgs/post-img1.jpg" alt="post-img" />
<p class="tag">fellowship</p>
<h2>Lessons learned building an education programme for developers</h2>
<Newsletter />

<style>
  /* DEMO OF STYLING IN PAGE */
  img {
    width: 80%;
    margin: 50px;
  }
</style>
