<script>
    import Hero from "$lib/components/layout/Hero.svelte";
    import Card from "$lib/components/ui/Card.svelte";
    import ContactForm from "$lib/components/ui/ContactForm.svelte";

</script>

<Hero />

<div class="container">
    <h2>Trusted By</h2>
    <div class="switcher">
        <Card title="National Co." />
        <Card title="Bestuvus" primary />
        <Card title="Munky-Chunks" secondary />
    </div>
</div>

<div class="container">
    <ContactForm />
</div>

