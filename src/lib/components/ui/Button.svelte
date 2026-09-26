<script>
    let { text='Text', type='button', onclick, disabled=false } = $props();
</script>

<button {type} {onclick} {disabled}>{text}</button>

<style>
    button {
        font-family: var(--font-body);
        padding: 0.5em 2em;
        background-color: var(--clr-primary);
        border: 1px solid var(--clr-light);
        border-radius: 100vw;
        opacity: 0.85;
        scale: 0.99;
        transition: opacity 0.2s, scale 0.2s;
        color: var(--clr-dark);
    }

    button:hover {
        opacity: 1;
        scale: 1;
    }
</style>