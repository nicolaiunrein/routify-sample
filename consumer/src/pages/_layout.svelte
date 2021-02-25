<script>
    import { url } from "@roxi/routify";
</script>

<!-- routify:options preload="proximity" -->
<h2>Demo project to illustrate roxiness/routify issue <b>#338</b></h2>
<a href={$url("./")}>Home</a>
<a href={$url("./Context")}>Context</a>
<a href={$url("./Error")}>Error</a>
<slot />

<style>
    :global(body) {
        padding: 50px;
    }
    :global(pre) {
        background-color: rgba(0, 0, 0, 0.1);
        border-radius: 20px;
        padding: 20px;
    }
    b {
        font-weight: bolder;
    }

    a {
        margin: 10px;
        font-size: large;
    }
</style>
