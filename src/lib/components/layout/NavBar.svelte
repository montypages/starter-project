<script>
    import logo from '$lib/assets/favicon.svg'
    import Button from '../ui/Button.svelte';

</script>

<nav>
    <div class="logo">
        <a href="/"><img src={logo} alt="logo"></a>
    </div>
    <ul class="nav-links" role='list'>
        <li><a>Events</a></li>
        <li><a>About</a></li>
        <li><Button text="Contact" /></li>
    </ul>
</nav>

<style>
    nav {
        display: flex;
        justify-content: space-between;
        padding: 0.25rem 1rem;
    }

    .logo {
        width: var(--size-1);
    }

    .nav-links {
        margin: 0;
        padding: 0;
        display: flex;
        align-items: center;
        gap: 2rem;
    }
</style>