<script lang="ts">
    import favicon from "$lib/assets/favicon.svg";
    import "../app.scss";
    let { children } = $props();
</script>

<svelte:head>
    <link rel="icon" href={favicon} />
    <title>asterisk by hactus | Desgin</title>
</svelte:head>
<nav></nav>
{@render children()}
