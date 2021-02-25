<script>
    import { Context } from "library";
    import { getContext } from "svelte";

    let this_ctx = getContext("routify");
</script>

<div class="container">
    <div>
        <h3>This Context</h3>
        <pre>{JSON.stringify($this_ctx, null, 2)}</pre>
    </div>

    <div>
        <h3>Library Context</h3>
        <Context />
    </div>
</div>

<style>
    .container {
        padding: 50px;
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 20px;
    }
</style>
