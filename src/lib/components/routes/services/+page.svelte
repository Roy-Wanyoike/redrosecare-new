<script>
    import Footer from "$lib/components/Footer.svelte";
    import Header from "$lib/components/Header.svelte";


var step=0;

</script>

<Header></Header>

<main>
    <!-- Banner -->
    <section class="section image-infinite-bg position-relative"
        style="background-size: cover; background-position: center ;padding: 15em 1em 15em 1em;"
        data-images='["image/picture5.png" , "image/picture2.png"]'>
        <div class="r-container h-100">
            <div class="image-overlay"></div>
            <div class="d-flex flex-column justify-content-center gap-3 h-100 position-relative"
                style="max-width: 768px; z-index: 2;">
                <h1 class="text-title text-white fw-bold font-1 lh-1">Redrose Care <br> Limited</h1>
                <p class="text-white f-18 text-font">At Red Rose Care Limited, we take pride in offering a range of personalized and compassionate services designed
                     to enhance the well-being and quality of life for our elderly residents. Our commitment to excellence is reflected in every aspect of the care
                      we provide, making us your go-to partner for a nurturing and supportive environment.





                </p>
                <div>
                    <a type="button" href="/about"
                        class="btn bg-accent-color text-font rounded-0">LEARN MORE</a>
                </div>
            </div>
        </div>
    </section>

    <section class="position-relative" style="margin-top: -80px;">
        <div class="r-container px-lg-0 px-4">
            <div class="overflow-hidden rounded-4">
                <div class="row row-cols-1 row-cols-lg-3">
                    <div class="col bg-accent-color-1 text-white">
                        <div class="d-flex flex-row gap-2 align-items-center  p-4">
                            <div class="rounded-circle bg-accent-color icon-box">
                                <i class="fa-solid fa-user-doctor"></i>
                            </div>
                            <div class="d-flex flex-column">
                                <span class="fw-bold font-1 fs-4">Our Services</span>
                                <span class="fw-bold font-1 fs-3 lh-1">
                                    Professional & Expert Nurses
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="col bg-accent-color text-white ">
                        <div class="d-flex flex-row gap-2 align-items-center  p-4">
                            <div class="rounded-circle bg-accent-color-2 icon-box">
                                <i class="fa-solid fa-stethoscope"></i>
                            </div>
                            <div class="d-flex flex-column">
                                <span class="fw-bold font-1 fs-4">Clinical Advice</span>
                                <span class="fw-bold font-1 fs-3 lh-1">
                                    Trusted Quality Care Solutions
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="col bg-accent-color-2 text-white">
                        <div class="d-flex flex-row gap-2 align-items-center  p-4">
                            <div class="rounded-circle bg-accent-color-1 icon-box">
                                <i class="fa-solid fa-earth-asia"></i>
                            </div>
                            <div class="d-flex flex-column">
                                <span class="fw-bold font-1 fs-4">Our Expertises</span>
                                <span class="fw-bold font-1 fs-3 lh-1">
                                    World Class Senior Services
                                </span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <!-- Welcome To Red Rose Care -->
    <section class="section">
        <div class="r-container">
            <div class="row row-cols-1 row-cols-lg-2">
                <div class="col mb-3 pe-lg-3 position-relative">
                    <div class="overlay right"></div>
                    <div class="position-relative pe-5">
                        <img src="image/image-600x700-1.jpg" alt="" class="img-fluid" style="z-index: -2;">
                        <div class="position-absolute bottom-0 start-0 ms-4 mb-4">
                            <div class="modal fade bg-overlay" id="exampleModal" tabindex="-1"
                                aria-labelledby="exampleModalLabel" aria-hidden="true">
                                <div class="modal-dialog modal-dialog-centered modal-lg">
                                
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col mb-3">
                    <div class="d-flex flex-column gap-3 p-3">
                        <h6 class="accent-color font-2 ">Welcome To Redrose Care</h6>
                        <h3 class="text-black font-1 lh-1 fw-semibold">See & Experience A New Perspective Of Life
                        </h3>
                        <p class="text-gray">
                            Discover a sanctuary of comfort at Homecare Limited. Embrace a new life perspective with personalized care, tranquility, and rejuvenation. Our promise
                        </p>
                        <div class="row row-cols-2">
                            <div class="col mb-2">
                                <div class="d-flex flex-row gap-2 align-items-center">
                                    <i class="fa-solid fa-circle-arrow-right accent-color"></i>
                                    <span class="text-gray">Tailored Comfort</span>
                                </div>
                            </div>
                            <div class="col mb-2">
                                <div class="d-flex flex-row gap-2 align-items-center">
                                    <i class="fa-solid fa-circle-arrow-right accent-color"></i>
                                    <span class="text-gray">Exceptional Care</span>
                                </div>
                            </div>
                            <div class="col mb-2">
                                <div class="d-flex flex-row gap-2 align-items-center">
                                    <i class="fa-solid fa-circle-arrow-right accent-color"></i>
                                    <span class="text-gray">Tranquil Living
                                    </span>
                                </div>
                            </div>
                            <div class="col mb-2">
                                <div class="d-flex flex-row gap-2 align-items-center">
                                    <i class="fa-solid fa-circle-arrow-right accent-color"></i>
                                    <span class="text-gray">Rejuvenation Hub</span>
                                </div>
                            </div>
                            <div class="col mb-2">
                                <div class="d-flex flex-row gap-2 align-items-center">
                                    <i class="fa-solid fa-circle-arrow-right accent-color"></i>
                                    <span class="text-gray">Personalized Services</span>
                                </div>
                            </div>
                            <div class="col mb-2">
                                <div class="d-flex flex-row gap-2 align-items-center">
                                    <i class="fa-solid fa-circle-arrow-right accent-color"></i>
                                    <span class="text-gray">Quality Lifestyle
                                    </span>
                                </div>
                            </div>
                        </div>
                        <div class="my-4 border-bottom w-100"></div>
                        <div class="row row-cols-1 row-cols-lg-2">
                            <div class="col mb-3">
                                <div
                                    class="d-flex flex-lg-row flex-column justify-content-lg-start align-items-center gap-2 justify-content-center">
                                    <div class="bg-accent-color text-white rounded-3 icon-box"
                                        style="font-size: 20px; width: 3rem; height: 3rem;">
                                        <i class="fa-solid fa-user-doctor"></i>
                                    </div>
                                    <span class="font-1 fs-3 lh-1 fw-semibold">Expert Nursing Staff</span>
                                </div>
                            </div>
                            <div class="col mb-3">
                                <div
                                    class="d-flex flex-lg-row flex-column justify-content-lg-start align-items-center gap-2 justify-content-center">
                                    <div class="bg-accent-color text-white rounded-3 icon-box"
                                        style="font-size: 20px; width: 3rem; height: 3rem;">
                                        <i class="fa-solid fa-house-medical-circle-check"></i>
                                    </div>
                                    <span class="font-1 fs-3 lh-1 fw-semibold">Safe Solution For Health</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Types Of Care -->





</main>
<Footer></Footer>