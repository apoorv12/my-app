<script context="module">
    export function load({ error }) {
        return {
            props: { message: error.message },
        };
    }
</script>

<script>
    export let message;
</script>

<div class="text-center font-bold p-20">
    <h1>You entered wrong URL</h1>
    <p>{message}</p>
</div>
