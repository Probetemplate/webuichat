<script lang="ts">
    import { onMount } from 'svelte';
    import 'bootstrap/dist/css/bootstrap.min.css';

    let message: string;

    onMount(() => {
        message = 'Hello, SvelteKit with TypeScript!';
    });
</script>

<main class="container">
    <h1 class="text-center mt-5">{message}</h1>
</main>
