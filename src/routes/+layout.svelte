<script lang="ts">
    import favicon from "$lib/assets/favicon.svg";
    import "../app.scss";
    let { children } = $props();
</script>

<svelte:head>
    <link rel="icon" href={favicon} />
    <title>a_risk</title>
</svelte:head>
<nav>
    <img src="" alt="some" />
    <a href="">link</a>
</nav>
{@render children()}
<footer>
    <div></div>
</footer>
