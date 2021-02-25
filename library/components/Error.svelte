<script>
    import { isActive } from "@roxi/routify";

    function onClick() {
        console.log('$isActive("./index") = ', $isActive("./index"));
    }
</script>

<button on:click={onClick}>Click me!</button>

<style>
    button {
        border: none;
        outline: none;
        background-color: red;
        color: white;
        width: 200px;
        height: 80px;
    }
</style>
