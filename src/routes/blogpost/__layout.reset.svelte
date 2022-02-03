<script>
    import Title from "$lib/header.svelte";
    import "../../app.css";
</script>

<header>
    <Title title="Blogpost new" />
</header>

<main>
    <!-- content -->
    <slot />
</main>

<footer>
    <p>Copyright AG. Advisers 2022</p>
</footer>

<style>
    header {
        text-align: center;
    }

    footer {
        text-align: center;
    }
</style>
