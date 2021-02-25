<script>
    import { getContext } from "svelte";
    let ctx = getContext("routify");
</script>

<pre>{JSON.stringify($ctx, null, 2)}</pre>
