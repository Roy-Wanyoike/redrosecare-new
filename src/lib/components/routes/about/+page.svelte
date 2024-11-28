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
                <h1 class="font-1 fw-bold text-white">About Us</h1>
                <nav aria-label="breadcrumb">
                    <ol class="breadcrumb">
                        <li class="breadcrumb-item fw-bold"><a href="/index">Home</a></li>
                        <li class="breadcrumb-item fw-bold active" aria-current="page">About Us</li>
                    </ol>
                </nav>
            </div>
        </div>
    </section>
    <!-- Welcome To Seniorsy -->

    <!-- Why Choose Seniorsy -->
    <section class="section">
        <div class="r-container">
            <div class="d-flex flex-lg-row flex-column-reverse">
                <div class="col mb-3">
                    <div class="d-flex flex-column gap-3 p-3 h-100 justify-content-center">
                        <h6 class="accent-color font-2 ">Why Choose Red Rose Care</h6>
                        <h3 class="text-black font-1 lh-1 fw-bold">Your Trusted Partner in Elderly Well-being
                        </h3>
                        <div class="d-flex flex-lg-row flex-column">
                           
                            <div class="col col-lg-8">
                                <div class="d-flex flex-column ps-3">
                                    <p class="fs-4">
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
                        <img src="image/image-600x700-2.jpg" alt="" class="img-fluid rounded-3"
                            style="z-index: -2;">
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

    <section class="section bg-light">
        <div class="r-container">
            <div class="d-flex flex-column gap-2 text-center">
                
                <h3 class="font-1 lh-1 fw-bold fs-1 mb-3">OUR QUALITIES</h3>
                <p class="text-gray mx-auto" style="max-width: 768px;">
                    Choosing Redrose Care means choosing a partner in your loved one's
                     journey towards a fulfilling and comfortable life in their later years. Our dedication to excellence
                      and a person-centered approach sets us apart, providing peace of mind for families and a home-like atmosphere
                       for our residents.
                </p>
                <div class="accordion d-flex flex-column gap-2 text-start" id="accordionExample">
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button class="accordion-button fw-bold" type="button" data-bs-toggle="collapse"
                                data-bs-target="#collapseOne" aria-expanded="false" aria-controls="collapseOne">
                                Compassionate and Skilled Caregivers
                            </button>
                        </h2>
                        <div id="collapseOne" class="accordion-collapse collapse show"
                            data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                                Our team consists of compassionate and highly skilled caregivers dedicated to 
                                providing personalized care for the elderly. We understand the unique needs of each individual and 
                                tailor our services accordingly.
                            </div>
                        </div>
                    </div>
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button class="accordion-button fw-bold collapsed" type="button"
                                data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false"
                                aria-controls="collapseTwo">
                                Holistic Approach to Well-being
                            </button>
                        </h2>
                        <div id="collapseTwo" class="accordion-collapse collapse"
                            data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                                Redrose Care takes a holistic approach to elderly care, focusing not only on physical health but also
                                 mental and emotional well-being. Our programs include stimulating activities and social engagement to
                                  enhance overall quality of life.
                            </div>
                        </div>
                    </div>
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button class="accordion-button fw-bold collapsed" type="button"
                                data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false"
                                aria-controls="collapseThree">
                                Safety and Security
                            </button>
                        </h2>
                        <div id="collapseThree" class="accordion-collapse collapse"
                            data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                                Your loved one's safety is our top priority. Our facilities are equipped with state-of-the-art
                                 security measures, and our staff is trained to respond effectively to any emergency situations.
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>



    <section class="section bg-light">
        <div class="r-container">
           
        </div>
    </section>


    <section class="section position-relative" style="background-image: url(image/image-1920x900-7.jpg);">
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