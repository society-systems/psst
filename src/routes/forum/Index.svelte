<script>
    import Posts from "../../components/forum/Posts.svelte";
</script>

<style>
    a {
        margin-bottom: var(--size-s);
        display: inline-block;
    }
</style>

<section>
    <h1>Forum</h1>
    <a href="#/forum/new" class="button">New Post</a>
    <Posts />
</section>
