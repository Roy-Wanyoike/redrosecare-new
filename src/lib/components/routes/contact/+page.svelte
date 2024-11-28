<script>
    import Header from "$lib/components/Header.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>
<Header></Header>
<main>
    <!-- Banner -->
    <section class="section position-relative" style="background-image: url(image/picture4.png);">
        <div class="r-container">
            <div class="image-overlay"></div>
            <div class="position-relative" style="z-index: 2;">
                <h1 class="font-1 fw-bold text-white">Contact Us</h1>
                <nav aria-label="breadcrumb">
                    <ol class="breadcrumb">
                        <li class="breadcrumb-item fw-bold"><a href="/">Home</a></li>
                        <li class="breadcrumb-item fw-bold active" aria-current="page">Contact Us</li>
                    </ol>
                </nav>
            </div>
        </div>
    </section>

    <section class="section">
        <div class="r-container">
            <div class="row row-cols-1 row-cols-lg-2">
                <div class="col mb-3">
                    <div class="d-flex flex-column gap-3 h-100 justify-content-center">
                        <h6 class="font-4 accent-color">Contact</h6>
                        <h3 class="font-1 lh-1 fw-bold fs-1">Compassion Is At The Heart Of Our Care</h3>
                        <p>Red Rose Care Limited is more than just a care facility; it's a community. We foster an atmosphere of camaraderie among residents, promoting social connections and a shared sense of belonging.</p>
                        <div class="d-flex flex-column">
                            <div class="py-1 border-bottom">
                                <h6 class="font-1 fw-bold">Opening Hours</h6>
                            </div>
                            <div class="py-2 border-bottom d-flex flex-row gap-5">
                                <span>Monday - Saturday</span>
                                <span class="d-flex align-items-center gap-2">
                                    <i class="fa-regular fa-clock accent-color"></i>
                                    08:00am - 07:00pm
                                </span>
                            </div>
                        </div>
                        <div class="d-flex flex-column gap-3">
                            <div class="d-flex flex-row gap-3 align-items-center">
                                <div class="bg-accent-color rounded-3 p-2 text-white" style="aspect-ratio: 1/1;">
                                    <h4 class="lh-1 m-0 p-0 fw-bold font-1">
                                        <i class="fa-solid fa-map-location-dot"></i>
                                    </h4>
                                </div>
                                <div class="d-flex flex-column">
                                    <h6 class="font-1 fw-bold lh-1 m-0 text-gray">
                                        Visit Us
                                    </h6>
                                    <span class="fs-4 fw-bold font-1">80 scrub Lane 
                                        Cumberland House 
                                        London NW10 6RF</span>
                                </div>
                            </div>
                            <div class="d-flex flex-row gap-3 align-items-center">
                                <div class="bg-accent-color rounded-3 p-2 text-white" style="aspect-ratio: 1/1;">
                                    <h4 class="lh-1 m-0 p-0 fw-bold font-1">
                                        <i class="fa-solid fa-envelope"></i>
                                    </h4>
                                </div>
                                <div class="d-flex flex-column">
                                    <h6 class="font-1 fw-bold lh-1 m-0 text-gray">
                                        Our Email
                                    </h6>
                                    <span class="fs-4 fw-bold font-1">info@redrosecare.com</span>
                                </div>
                            </div>
                            <div class="d-flex flex-row gap-3 align-items-center">
                                <div class="bg-accent-color rounded-3 p-2 text-white" style="aspect-ratio: 1/1;">
                                    <h4 class="lh-1 m-0 p-0 fw-bold font-1">
                                        <i class="fa-solid fa-phone"></i>
                                    </h4>
                                </div>
                                <div class="d-flex flex-column">
                                    <h6 class="font-1 fw-bold lh-1 m-0 text-gray">
                                        Our Number
                                    </h6>
                                    <span class="fs-4 fw-bold font-1">+44 7904096889</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col mb-3">
                    <div class="bg-accent-color rounded-4">
                        <div class="h-100 d-flex flex-column p-5">
                            <h6 class="font-2 text-white">Fill The Form</h6>
                            <h3 class="font-1 lh-1 fw-bold fs-1 mb-3 text-white">Get In Touch</h3>
                            <div class="success_msg toast align-items-center w-100 shadow-none mb-3 border border-success rounded-0 my-4"
                                role="alert" aria-live="assertive" aria-atomic="true">
                                <div class="d-flex p-2">
                                    <div
                                        class="toast-body f-18 d-flex flex-row gap-3 align-items-center text-success">
                                        <i class="fa-solid fa-check f-36 text-success"></i>
                                        Your Message Successfully Send.
                                    </div>
                                    <button type="button"
                                        class="me-2 m-auto bg-transparent border-0 ps-1 pe-0 text-success"
                                        data-bs-dismiss="toast" aria-label="Close"><i
                                            class="fa-solid fa-xmark"></i></button>
                                </div>
                            </div>
                            <div class="error_msg toast align-items-center w-100 shadow-none border-danger mb-3 my-4 border rounded-0"
                                role="alert" aria-live="assertive" aria-atomic="true">
                                <div class="d-flex p-2">
                                    <div
                                        class="toast-body f-18 d-flex flex-row gap-3 align-items-center text-danger">
                                        <i class="fa-solid fa-triangle-exclamation f-36 text-danger"></i>
                                        Something Wrong ! Send Form Failed.
                                    </div>
                                    <button type="button"
                                        class="me-2 m-auto bg-transparent border-0 ps-1 pe-0 text-danger"
                                        data-bs-dismiss="toast" aria-label="Close"><i
                                            class="fa-solid fa-xmark"></i></button>
                                </div>
                            </div>
                            <form action="#"
                                class="d-flex flex-column h-100 justify-content-center w-100 needs-validation mb-3 form"
                                novalidate>
                                <div class="mb-3">
                                    <input type="text" class="form-control py-2 px-4" name="name" id="name"
                                        placeholder="Name" required>
                                    <div class="invalid-feedback">
                                        The field is required.
                                    </div>
                                </div>
                                <div class="mb-3">
                                    <input type="email" class="form-control py-2 px-4" name="email" id="email"
                                        placeholder="Email" required>
                                    <div class="invalid-feedback">
                                        The field is required.
                                    </div>
                                </div>
                                <div class="mb-3">
                                    <input type="text" class="form-control py-2 px-4" name="subject" id="subject"
                                        placeholder="Subject" required>
                                    <div class="invalid-feedback">
                                        The field is required.
                                    </div>
                                </div>
                                <div class="mb-3">
                                    <textarea class="form-control py-2 px-4" id="message" name="message" rows="5"
                                        placeholder="Message"></textarea>
                                </div>
                                <div class="mb-3">
                                    <button type="submit" class="btn submit_form py-3">
                                        Send Message
                                    </button>
                                </div>
                            </form>

                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="pb-5">
        <div class="r-container">
            <div class="mb-3">
               
    <iframe
    class="maps overflow-hidden rounded-3" 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2482.1740508353832!2d-0.23910562261522686!3d51.52836740917052!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x487611ccddb194dd%3A0xafa586f94dac9c62!2sCumberland%20House%2C%2080%20Scrubs%20Ln%2C%20London%20NW10%206RF%2C%20UK!5e0!3m2!1sen!2ske!4v1706136918479!5m2!1sen!2ske" 
    width="600" 
    height="450"
    style="border:0;" 
    loading="lazy" 
    referrerpolicy="no-referrer-when-downgrade"
    title="Google Maps Location of Cumberland House, London">
</iframe>
            </div>
        </div>
    </section>

</main>


<Footer></Footer>