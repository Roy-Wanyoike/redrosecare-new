<script>
    export let title = "Home Cleaning";
    export let description =
        "Keep your home spotless and welcoming with our professional cleaning services. We tailor our cleaning to meet your needs.";
    export let image = "/images/home-cleaning.jpg"; // Replace with actual image path
</script>

<section>
    <h1>{title}</h1>
    <img src={image} alt={title} class="service-image" />
    <p>{description}</p>
    <a href="/services" class="btn">Back to Services</a>
</section>

<style>
    /* Same styles as Elderly Care page */
    @import './elderly-care.svelte';
</style>
