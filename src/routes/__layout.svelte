<script>
    import '../styles/tailwind.css';
    import Nav from '../components/nav.svelte';
</script>

<div class="p-8 max-w-6xl mx-auto">
    <Nav />
    <slot />
</div>
