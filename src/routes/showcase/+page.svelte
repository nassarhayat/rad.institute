<script>
    import Newsletter from "$lib/components/Newsletter.svelte";
</script>


<h1>Showcase</h1>
<div class="feed">
    <a href="/posts/1" class="post">
        <img src="/imgs/post-img.png" alt="post-img" class="post-img">
        <h2>Lessons learned building an education programme for developers</h2>
        <p>article</p>
    </a>
    <a href="/posts/1" class="post">
        <img src="/imgs/post-img.png" alt="post-img" class="post-img">
        <h2>Lessons learned building an education programme for developers</h2>
        <p>article</p>
    </a>
    <a href="/posts/1" class="post">
        <img src="/imgs/post-img.png" alt="post-img" class="post-img">
        <h2>Lessons learned building an education programme for developers</h2>
        <p>article</p>
    </a>
    <a href="/posts/1" class="post">
        <img src="/imgs/post-img.png" alt="post-img" class="post-img">
        <h2>Lessons learned building an education programme for developers</h2>
        <p>article</p>
    </a>
</div>
<Newsletter />

<style>
    .feed {
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