<script>
    import Title from "$lib/header.svelte";
    import "../app.css";
</script>

<header>
    <Title />
</header>

<main>
    <!-- content -->
    <slot />
</main>

<footer>
    <p>Copyright 2022</p>
</footer>

<style>
    header {
        text-align: center;
    }

    footer {
        text-align: center;
    }
</style>
