<script>
    import Header from "$lib/components/Header.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<Header></Header>
<main>
    <!-- Banner -->
    <section class="section position-relative" style="background-image: url(image/image-1920x900-7.jpg);">
        <div class="r-container">
            <div class="image-overlay"></div>
            <div class="position-relative" style="z-index: 2;">
                <h1 class="font-1 fw-bold text-white">Help</h1>
                <nav aria-label="breadcrumb">
                    <ol class="breadcrumb">
                        <li class="breadcrumb-item fw-bold"><a href="/">Home</a></li>
                        <li class="breadcrumb-item fw-bold active" aria-current="page">Help</li>
                    </ol>
                </nav>
            </div>
        </div>
    </section>

    <section class="section">
        <div class="r-container">
            <div class="row row-cols-1 row-cols-lg-4">
                <div class="col">
                    <div
                        class="card d-flex flex-column justify-content-center align-items-center text-center p-4 gap-3">
                        <div class="rounded-circle p-1 bg-accent-color d-flex justify-content-center align-items-center text-white"
                            style="width: 4rem; height: 4rem; font-size: 2.3rem;">
                            <i class="fa-solid fa-headset"></i>
                        </div>
                        <h5 class="font-1 fw-bold m-0 lh-1">Costumer Service</h5>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        <a href="/contact" class="btn fw-bold rounded-0 border-0 border-bottom border-black">Send A
                            Ticket</a>
                    </div>
                </div>
                <div class="col">
                    <div
                        class="card d-flex flex-column justify-content-center align-items-center text-center p-4 gap-3">
                        <div class="rounded-circle p-1 bg-accent-color d-flex justify-content-center align-items-center text-white"
                            style="width: 4rem; height: 4rem; font-size: 2.3rem;">
                            <i class="fa-solid fa-book-open"></i>
                        </div>
                        <h5 class="font-1 fw-bold m-0 lh-1">Service</h5>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        <a href="/services" class="btn fw-bold rounded-0 border-0 border-bottom border-black">All
                            Services</a>
                    </div>
                </div>
                <div class="col">
                    <div
                        class="card d-flex flex-column justify-content-center align-items-center text-center p-4 gap-3">
                        <div class="rounded-circle p-1 bg-accent-color d-flex justify-content-center align-items-center text-white"
                            style="width: 4rem; height: 4rem; font-size: 2.3rem;">
                            <i class="fa-solid fa-user-doctor"></i>
                        </div>
                        <h5 class="font-1 fw-bold m-0 lh-1">Doctor & Nurse</h5>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        <a href="/team" class="btn fw-bold rounded-0 border-0 border-bottom border-black">All Team</a>
                    </div>
                </div>
                <div class="col">
                    <div
                        class="card d-flex flex-column justify-content-center align-items-center text-center p-4 gap-3">
                        <div class="rounded-circle p-1 bg-accent-color d-flex justify-content-center align-items-center text-white"
                            style="width: 4rem; height: 4rem; font-size: 2.3rem;">
                            <i class="fa-solid fa-rotate"></i>
                        </div>
                        <h5 class="font-1 fw-bold m-0 lh-1">Company Policy</h5>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        <a href="/" class="btn fw-bold rounded-0 border-0 border-bottom border-black">Read More</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="section bg-light">
        <div class="r-container">
            <div class="d-flex flex-column gap-2 text-center">
                <h6 class="font-2 accent-color">FAQ</h6>
                <h3 class="font-1 lh-1 fw-bold fs-1 mb-3">The Most Question We Had</h3>
                <p class="text-gray mx-auto" style="max-width: 768px;">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus sed pharetra erat. Integer
                    ullamcorper quis est in vehicula. Sed eu cursus dui. Aenean vel velit non neque dictum interdum
                    a nec ex.
                </p>
                <div class="accordion d-flex flex-column gap-2 text-start" id="accordionExample">
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button class="accordion-button fw-bold" type="button" data-bs-toggle="collapse"
                                data-bs-target="#collapseOne" aria-expanded="false" aria-controls="collapseOne">
                                How To Change My Photo From Admin Dashboard ?
                            </button>
                        </h2>
                        <div id="collapseOne" class="accordion-collapse collapse show"
                            data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                                Suspendisse cursus arcu et purus consectetur luctus. Ut ultricies dapibus auctor.
                                Etiam ullamcorper nunc at augue dictum fermentum. Vivamus id eleifend ligula. Nunc
                                blandit efficitur magna et suscipit. Donec sed eleifend massa. Phasellus nec dictum
                                nulla. Quisque ac metus odio. Phasellus vulputate ullamcorper purus, dapibus
                                faucibus elit convallis eget. Maecenas interdum massa quis tempus tincidunt. Donec
                                eget fringilla magna. Etiam vel mi massa. Praesent rhoncus lorem non condimentum
                                maximus.
                                <br><br>
                                Integer euismod suscipit arcu, at dictum ante. Donec quis metus nunc. Vestibulum in
                                tellus auctor, fringilla sem ut, volutpat tellus. Suspendisse eu interdum ante, vel
                                molestie diam. Donec aliquet consequat feugiat. Nullam dapibus, velit ornare
                                accumsan ultrices, ipsum metus aliquet diam, eu congue nisl orci commodo augue.
                            </div>
                        </div>
                    </div>
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button class="accordion-button fw-bold collapsed" type="button"
                                data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false"
                                aria-controls="collapseTwo">
                                How To Change My Password Easily ?
                            </button>
                        </h2>
                        <div id="collapseTwo" class="accordion-collapse collapse"
                            data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                                Nam quis felis vulputate, auctor ligula at, tincidunt nulla. Aenean elementum, orci
                                eu malesuada bibendum, nisl enim fringilla arcu, a congue justo ex ut purus. Proin
                                pulvinar quam eget urna dignissim lobortis. Vivamus ac venenatis enim.
                                <br><br>
                                Curabitur molestie placerat fermentum. Proin vitae orci tellus. Morbi suscipit nulla
                                metus, eu vulputate erat ultricies a. Etiam vitae erat vitae neque varius mollis
                                quis quis eros. Proin vehicula tincidunt ligula at viverra. Sed sed laoreet neque.
                            </div>
                        </div>
                    </div>
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button class="accordion-button fw-bold collapsed" type="button"
                                data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false"
                                aria-controls="collapseThree">
                                How To Change My Subscription Plan Using PayPal
                            </button>
                        </h2>
                        <div id="collapseThree" class="accordion-collapse collapse"
                            data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                                Duis nec imperdiet mi. Morbi bibendum dui quis vulputate tristique. Proin aliquet
                                elementum felis, ac volutpat tortor. Donec ut pellentesque elit. Aenean hendrerit
                                bibendum mauris. Sed aliquam quis mauris nec sodales.
                                <br><br>
                                Etiam quis lectus sagittis libero tempus elementum. Vestibulum et tortor risus.
                                Donec sit amet nibh eu felis lobortis laoreet eu vitae urna. Proin convallis
                                malesuada nibh, at efficitur nunc sollicitudin vitae. Duis ut odio leo.
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- News & Article -->
    <section class="section">
        <div class="r-container">
            <div class="d-flex flex-column gap-3">
                <div class="d-flex flex-lg-row flex-column text-lg-start text-center gap-lg-4 gap-2">
                    <div class="col col-lg-3">
                        <h6 class="font-2 accent-color">News & Article</h6>
                        <h3 class="font-1 lh-1 fw-bold fs-1 mb-3">Our Latest News</h3>
                    </div>
                    <div class="col col-lg-7">
                        <p class="text-gray">Fusce non egestas felis, in rhoncus est. Morbi non congue orci. Sed
                            venenatis varius
                            convallis. Aenean vitae hendrerit est, eu molestie orci. Vivamus consectetur molestie
                            lacus, at mattis augue porta et.</p>
                    </div>
                    <div class="col col-lg-2">
                        <a href="/" type="button" class="btn bg-accent-color p-3">View More</a>
                    </div>
                </div>
                <div class="row row-cols-1 row-cols-lg-3">
                    <div class="col mb-3">
                        <div class="card border border-light-subtle">
                            <img src="image/image-600x400-5.jpg" class="card-img-top" alt="...">
                            <div class="card-body px-3 py-4">
                                <h6 class="font-1 lh-1 fw-bold">Cherishing Life, Bringing Independence A Little
                                    Closer To Home</h6>
                                <p class="text-gray">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                                    Integer tincidunt maximus malesuada. Quisque ut ipsum…</p>
                                <a type="button" href="/mentalhealth" class="btn bg-accent-color py-3 px-4 text-white">Learn
                                    More</a>
                            </div>
                        </div>
                    </div>
                    <div class="col mb-3">
                        <div class="card border border-light-subtle">
                            <img src="image/image-600x400-4.jpg" class="card-img-top" alt="...">
                            <div class="card-body px-3 py-4">
                                <h6 class="font-1 lh-1 fw-bold">Connected Living Strives To Curb Loneliness Amongst
                                    Seniors</h6>
                                <p class="text-gray">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                                    Integer tincidunt maximus malesuada. Quisque ut ipsum…</p>
                                <a type="button" href="/autism" class="btn bg-accent-color py-3 px-4 text-white">Learn
                                    More</a>
                            </div>
                        </div>
                    </div>
                    <div class="col mb-3">
                        <div class="card border border-light-subtle">
                            <img src="image/image-600x400-1.jpg" class="card-img-top" alt="...">
                            <div class="card-body px-3 py-4">
                                <h6 class="font-1 lh-1 fw-bold">Metabolism Changes With Age, Just Not When You Might
                                    Think</h6>
                                <p class="text-gray">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                                    Integer tincidunt maximus malesuada. Quisque ut ipsum…</p>
                                <a type="button" href="/services" class="btn bg-accent-color py-3 px-4 text-white">Learn
                                    More</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</main>        


<Footer></Footer>