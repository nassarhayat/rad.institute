<script>
    import Newsletter from "$lib/components/Newsletter.svelte";
</script>


<h1>Welcome</h1>
<div class="home-feed">
    <a href="/posts/hi-brandon" class="post">
        <img src="/imgs/post-img.png" alt="post-img" class="post-img">
        <h2>Lessons learned building an education programme for developers</h2>
        <p>article</p>
    </a>
    <a href="/posts/jumping-dogs" class="post">
        <img src="/imgs/post-img.png" alt="post-img" class="post-img">
        <h2>Lessons learned building an education programme for developers</h2>
        <p>article</p>
    </a>
    <a href="/posts/flying-cats" class="post">
        <img src="/imgs/post-img.png" alt="post-img" class="post-img">
        <h2>Lessons learned building an education programme for developers</h2>
        <p>article</p>
    </a>
    <a href="/posts/hello-mate" class="post">
        <img src="/imgs/post-img.png" alt="post-img" class="post-img">
        <h2>Lessons learned building an education programme for developers</h2>
        <p>article</p>
    </a>
</div>
<Newsletter />

<style>
    .home-feed {
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-template-rows: 1fr 1fr;
        grid-gap: 40px;
        margin: 20px;
    }
    .post-img {
        width: 100%;
    }
</style>