<script>
    import Header from "$lib/components/Header.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<Header></Header>
<main>
    <!-- Banner -->
    <section class="section position-relative" style="background-image: url(image/picture15.png);">
        <div class="r-container">
            <div class="image-overlay"></div>
            <div class="position-relative" style="z-index: 2;">
                <h1 class="font-1 fw-bold text-white">Mental Health</h1>
                <nav aria-label="breadcrumb">
                    <ol class="breadcrumb">
                        <li class="breadcrumb-item fw-bold"><a href="/index">Home</a></li>
                        <li class="breadcrumb-item fw-bold active" aria-current="page">Mental Health</li>
                    </ol>
                </nav>
            </div>
        </div>
    </section>
    <!-- Welcome To Seniorsy -->
    <section class="section bg-light">
        <div class="r-container">
            <div class="d-flex flex-column gap-2 text-center">
                
                <h3 class="font-1 lh-1 fw-bold fs-1 mb-3">Welcome to RedRose Care - Nurturing Mental Wellness</h3>
                <p class="text-gray mx-auto" style="max-width: 768px;">
                    RedRose Care is aware of the connection between mental health and general wellbeing. This page on mental health care
                     offers a haven for anyone looking for thorough information, empathetic help, and a supportive community that promotes 
                     mental wellbeing.
                </p>
                <section class="section">
                    <div class="r-container">
                        <div class="d-flex flex-lg-row flex-column-reverse">
                            <div class="col mb-3">
                                <div class="d-flex flex-column gap-3 p-3 h-100 justify-content-center">
                                    <h6 class="accent-color font-2 ">Mental Health</h6>
                                    <div class="d-flex flex-lg-row flex-column">
                                       
                                        <div class="col col-lg-8">
                                            <div class="text-left">
                                                <p>
                                                    At Redrose Care, we understand the importance of selecting the right care provider for your elderly family members. 
                                                    Our commitment to excellence and compassionate service sets us apart as a trusted partner in ensuring the well-being
                                                     and happiness of your loved ones. Here's why you should choose Redrose Care:
                                                </p>
                                               
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="col mb-5 pe-lg-3 position-relative">
                                <div class="overlay left"></div>
                                <div class="position-relative ps-5">
                                    <img src="image/picture16.png" alt="" class="img-fluid rounded-3" 
                                        style="max-height: 800px;">
                                    <div class="position-absolute bottom-0 end-0 d-flex justify-content-end">
                                        <div class=" bg-accent-color rounded-3 p-4 w-75" style="margin-bottom: -3rem;">
                                            <h6 class="font-1 text-white fw-bold">The Patient Is First Priority In Our Passion
                                            </h6>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </section>
                <div class="black-line">
                    <style>
                         .black-line {
      border-top: 1px solid #000; /* Black color */
      margin-top: 20px; /* Adjust the margin as needed */
      margin-bottom: 20px; /* Adjust the margin as needed */
    }
                    </style>
                </div>
                
                <hr class="my-4 color-black">
                <div class=" accordion-body text-left mt-5">
                    <h3 class="font-1 lh-1 fw-bold fs-1 mb-3 text-center">HOW TO GET STARTED</h3>
                    <ol>
                        <li>Contact Us: Reach out to our friendly team to discuss your needs and learn more about our services.</li>
                        <li>Assessment: Our experts will conduct a thorough assessment to understand the individual's strengths, challenges, and goals.</li>
                        <li>Personalized Plan: Based on the assessment, we will create a personalized care plan outlining the recommended services and interventions.</li>
                        <li>Ongoing Support: RedRose Care provides ongoing support and guidance, adapting the care plan as needed to ensure continued progress and well-being.</li>
                    </ol>
                </div>
                <div class="black-line">
                <h3 class="font-1 lh-1 fw-bold fs-1 mb-3 mt-5">Join Us on the Journey to Mental Wellness</h3>
                <p class="text-gray mx-auto" style="max-width: 768px;">
                    RedRose Care is here to support you on your journey to mental wellness. Together, let's break 
                    the stigma surrounding mental health, foster understanding, and
                     create a community where everyone feels empowered to prioritize their mental well-being.
                </p>

            </div>
            
        </div>
    </section>
    <!-- Why Choose Seniorsy -->
   
    

    <section class="section bg-light">
        
        <div class="r-container">
            <div class="d-flex flex-column gap-3 justify-content-center text-center">
                <h6 class="accent-color font-2 ">OUR SERVICES</h6>
                <h3 class="text-black font-1 lh-1 fw-semibold">Providing Quality Senior Care</h3>
                <p class="text-gray mx-auto" style="max-width: 768px;">
                    Homecare Limited, where a new perspective on life unfolds. Explore our diverse types of care, dedicated to providing quality senior living experiences with compassion, support, and excellence
                </p>
                <div class="row row-cols-1 row-cols-lg-3">
                    <div class="col">
                        <div class="card p-3 with-border-bottom border-0 shadow rounded-3">
                            <img src="image/picture11.png" class="card-img-top rounded-3" alt="...">
                            <div class="card-body ">
                                <h5 class="font-1 fw-bold">Live-in Care</h5>
                                <p class="text-gray">As viable alternative to residential care, live-in care is the perfect solution for round-the clock support in your own home</p>
                                <div class="d-flex justify-content-center">
                                    <a type="button" href="/services"
                                        class="btn post-button font-2 d-flex flex-row align-items-center gap-2">Talk to us<i class="fa-solid fa-circle-arrow-right mt-1"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card p-3 with-border-bottom border-0 shadow rounded-3">
                            <img src="image/picture12.png" class="card-img-top rounded-3" alt="...">
                            <div class="card-body ">
                                <h5 class="font-1 fw-bold">Hourly visiting care</h5>
                                <p class="text-gray">From 30 minutes per week to regular visits throughout the day, visiting care provides the support you need, whenever you need it.</p>
                                <div class="d-flex justify-content-center">
                                    <a type="button" href="/services"
                                        class="btn post-button font-2 d-flex flex-row align-items-center gap-2">Talk to us <i class="fa-solid fa-circle-arrow-right mt-1"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card p-3 with-border-bottom border-0 shadow rounded-3">
                            <img src="image/picture13.png" class="card-img-top rounded-3" alt="...">
                            <div class="card-body ">
                                <h5 class="font-1 fw-bold">Dementia care</h5>
                                <p class="text-gray">As one of the UKs leading dementia home care providers, our dementia care provides specialist support to you and your family.</p>
                                <div class="d-flex justify-content-center">
                                    <a type="button" href="/services"
                                        class="btn post-button font-2 d-flex flex-row align-items-center gap-2">Talk to us<i class="fa-solid fa-circle-arrow-right mt-1"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="d-flex justify-content-center my-4">
                    <a href="/services" type="button" class="btn bg-accent-color p-3 font-2">All Services</a>
                </div>
            </div>
        </div>
    </section>

<section class="section position-relative" style="background-image: url(image/picture14.png);">
        <div class="r-container">
            <div class="image-overlay"></div>
            <div class="position-relative" style="z-index: 2;">
                <h1 class="font-1 fw-bold text-white">Our Team</h1>
                <nav aria-label="breadcrumb">
                    <ol class="breadcrumb">
                        <li class="breadcrumb-item fw-bold"><a href="/">Home</a></li>
                        <li class="breadcrumb-item fw-bold active" aria-current="page">Team</li>
                    </ol>
                </nav>
            </div>
        </div>
    </section>

    <section class="section">
        <div class="r-container">
            <div class="d-flex flex-column gap-3 text-center">
                <h6 class="font-2 accent-color">Meet Our Beloved Nurse & Doctor</h6>
                <h3 class="font-1 lh-1 fw-bold fs-1 mb-3">Always Here For You & Them</h3>
                <div class="row row-cols-1 row-cols-lg-3">
                    <div class="col mb-3">
                        <div class="position-relative overflow-hidden rounded-3">
                            <img src="image/image-600x800-1.jpg" alt="" class="img-fluid">
                            <div class="position-absolute bottom-0 px-3 pb-5 w-100">
                                <div class="w-100 position-relative overflow-hidden rounded-3">
                                    <div class="image-overlay-2"></div>
                                    <div class="d-flex flex-column p-3 position-relative" style="z-index: 2;">
                                        <h4 class="text-white font-1 fw-bold m-0 ">Elsa verina</h4>
                                        <span class="text-white">Expert Team</span>
                                        <div class="social-container justify-content-center gap-2 mt-3">
                                            <a href="https://www.facebook.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-facebook"></i>
                                            </a>
                                            <a href="https://www.twitter.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-twitter"></i>
                                            </a>
                                            <a href="https://www.youtube.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-linkedin"></i>
                                            </a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col mb-3">
                        <div class="position-relative overflow-hidden rounded-3">
                            <img src="image/image-600x800-2.jpg" alt="" class="img-fluid">
                            <div class="position-absolute bottom-0 px-3 pb-5 w-100">
                                <div class="w-100 position-relative overflow-hidden rounded-3">
                                    <div class="image-overlay-2"></div>
                                    <div class="d-flex flex-column p-3 position-relative" style="z-index: 2;">
                                        <h4 class="text-white font-1 fw-bold m-0 ">Kumto Warming</h4>
                                        <span class="text-white">Expert Team</span>
                                        <div class="social-container justify-content-center gap-2 mt-3">
                                            <a href="https://www.facebook.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-facebook"></i>
                                            </a>
                                            <a href="https://www.twitter.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-twitter"></i>
                                            </a>
                                            <a href="https://www.youtube.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-linkedin"></i>
                                            </a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col mb-3">
                        <div class="position-relative overflow-hidden rounded-3">
                            <img src="image/image-600x800-3.jpg" alt="" class="img-fluid">
                            <div class="position-absolute bottom-0 px-3 pb-5 w-100">
                                <div class="w-100 position-relative overflow-hidden rounded-3">
                                    <div class="image-overlay-2"></div>
                                    <div class="d-flex flex-column p-3 position-relative" style="z-index: 2;">
                                        <h4 class="text-white font-1 fw-bold m-0 ">Puri Maha</h4>
                                        <span class="text-white">Expert Team</span>
                                        <div class="social-container justify-content-center gap-2 mt-3">
                                            <a href="https://www.facebook.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-facebook"></i>
                                            </a>
                                            <a href="https://www.twitter.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-twitter"></i>
                                            </a>
                                            <a href="https://www.youtube.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-linkedin"></i>
                                            </a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col mb-3">
                        <div class="position-relative overflow-hidden rounded-3">
                            <img src="image/image-600x800-4.jpg" alt="" class="img-fluid">
                            <div class="position-absolute bottom-0 px-3 pb-5 w-100">
                                <div class="w-100 position-relative overflow-hidden rounded-3">
                                    <div class="image-overlay-2"></div>
                                    <div class="d-flex flex-column p-3 position-relative" style="z-index: 2;">
                                        <h4 class="text-white font-1 fw-bold m-0 ">Dyas Kardinal</h4>
                                        <span class="text-white">Expert Team</span>
                                        <div class="social-container justify-content-center gap-2 mt-3">
                                            <a href="https://www.facebook.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-facebook"></i>
                                            </a>
                                            <a href="https://www.twitter.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-twitter"></i>
                                            </a>
                                            <a href="https://www.youtube.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-linkedin"></i>
                                            </a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col mb-3">
                        <div class="position-relative overflow-hidden rounded-3">
                            <img src="image/image-600x800-5.jpg" alt="" class="img-fluid">
                            <div class="position-absolute bottom-0 px-3 pb-5 w-100">
                                <div class="w-100 position-relative overflow-hidden rounded-3">
                                    <div class="image-overlay-2"></div>
                                    <div class="d-flex flex-column p-3 position-relative" style="z-index: 2;">
                                        <h4 class="text-white font-1 fw-bold m-0 ">Kelvin</h4>
                                        <span class="text-white">Expert Team</span>
                                        <div class="social-container justify-content-center gap-2 mt-3">
                                            <a href="https://www.facebook.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-facebook"></i>
                                            </a>
                                            <a href="https://www.twitter.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-twitter"></i>
                                            </a>
                                            <a href="https://www.youtube.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-linkedin"></i>
                                            </a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col mb-3">
                        <div class="position-relative overflow-hidden rounded-3">
                            <img src="image/image-600x800-6.jpg" alt="" class="img-fluid">
                            <div class="position-absolute bottom-0 px-3 pb-5 w-100">
                                <div class="w-100 position-relative overflow-hidden rounded-3">
                                    <div class="image-overlay-2"></div>
                                    <div class="d-flex flex-column p-3 position-relative" style="z-index: 2;">
                                        <h4 class="text-white font-1 fw-bold m-0 ">Elsa verina</h4>
                                        <span class="text-white">Expert Team</span>
                                        <div class="social-container justify-content-center gap-2 mt-3">
                                            <a href="https://www.facebook.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-facebook"></i>
                                            </a>
                                            <a href="https://www.twitter.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-twitter"></i>
                                            </a>
                                            <a href="https://www.youtube.com/" class="social-item bg-accent-color-1">
                                                <i class="fa-brands fa-linkedin"></i>
                                            </a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="section bg-light">
        <div class="r-container">
            <div class="d-flex flex-column gap-3 justify-content-center text-center">
                <h2 class="accent-color font-2 ">OUR VISION</h2>
                <p class="text-black mx-auto" style="max-width: 768px;">
                    Red Rose Care Limited, where a new perspective on life unfolds. Explore our diverse types of care, dedicated to providing quality senior living experiences with compassion, support, and excellence
                </p>
                <div class="d-flex flex-column gap-3 justify-content-center text-center">
                    <h2 class="accent-color font-2 ">OUR PHILOSOPHY</h2>
                    <p class="text-black mx-auto" style="max-width: 768px;">
                        At Red Rose Care Limited, we believe that every individual deserves to age with dignity and grace. Our philosophy is rooted in the 
                        understanding that elderly care is not just about addressing physical health but also nurturing emotional and mental well-being. We strive
                         to create an environment that empowers residents to lead fulfilling lives, embracing their unique stories and contributions.
                    </p>
                </div>
            </div>
        </div>
    </section>
</main>
<Footer></Footer>