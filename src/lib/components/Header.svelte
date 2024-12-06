<script>
    let services = [
    { name: "Elderly Care", link: "/services/elderly-care" }, 
    { name: "Home Cleaning", link: "/services/home-cleaning" },
    { name: "Post-Surgery Care", link: "/services/post-surgery-care" },
    { name: "Companion Care", link: "/services/companion-care" },
    { name: "Palliative Care", link: "/services/palliative-care" }, 
    { name: "Child Care", link: "/services/child-care" }, 
    { name: "Meal Preparation", link: "/services/meal-preparation" },
    { name: "Respite Care", link: "/services/respite-care" },
    { name: "Dementia and Alzheimer’s Care", link: "/services/dementia-and-Alzheimer" },
    { name: "Transportation Assistance", link: "/services/transportation-assistance" },
    {name: "Autismal", link: "/services/autism"},
    {name: "Mental Health", link: "/services/mental-health"},
    {name: "Occupational Therapy", link: "/services/occupational-therapy"},
    {name: "Speech Therapy", link: "/services/speech-therapy"},
    {name: "Physical Therapy", link: "/services/physical-therapy"},
    {name: "Psychotherapy", link: "/services/psychotherapy"},
    {name: "Nutritionists", link: "/services/nutrition"},
    {name: "Support Groups", link: "/services/support-groups"}, 
    {name: "Yoga and Meditation", link: "/services/yoga-and-meditation"},
    {name: "Grief Counseling", link: "/services/grief-counseling"},
    {name: "Counseling for Addiction", link: "/services/counseling-for-addiction"},
  ];

  let dropdownOpen = false;
  </script>

    <!-- Top-Header-Section -->
    <div class="home-header-section home-header-section1">
        <div class="header-top bg-dark py-2">
            <div class="container">
                <div class="row align-items-center">
                    <div class="col-lg-6 col-md-6 d-none d-md-block">
                        <div class="header-left d-table-cell align-middle">
                            <div class="phone-icon d-inline-block text-white"><i class="fa-solid fa-phone-volume"></i></div>
                            <p class="free-consultation-text d-inline-block mb-0 text-white">For a free consultation: <a href="tel:+123456789" class="text-decoration-none text-luminous-green">0800 123 45 67 890</a></p>
                        </div>
                    </div>
                    <div class="col-lg-6 col-md-6">
                        <div class="header-right float-md-right">
                            <ul class="list-unstyled d-flex justify-content-end mb-0">
                                <li class="d-inline-block mx-3"><i class="fa-sharp fa-solid fa-envelope text-white"></i><a class="email-span text-decoration-none text-white" href="mailto:info@redrosecare.com">info@redrosecare.com</a></li>
                                <li class="d-inline-block"><i class="fa-solid fa-user text-white"></i><a class="user-span text-decoration-none text-white" href="lib/components/Login.svelte">Login</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Header Section -->
        <header class="header sticky-top">
            <div class="main-header">
                <div class="container">
                    <nav class="navbar navbar-expand-lg navbar-dark p-0">
                        <a class="navbar-brand" href="#/">
                            <img src="/images/nobglogo.png" alt="Logo" class="img-fluid logo-size">
                        </a>
                        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                            <span class="navbar-toggler-icon"></span>
                        </button>
                        <div class="collapse navbar-collapse" id="navbarSupportedContent">
                            <ul class="navbar-nav ml-auto">
                                <li class="nav-item">
                                    <a class="nav-link text-decoration-none text-white" href="#/">HOME</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link text-decoration-none text-white" href="/about">About</a>
                                </li>
                                <li class="nav-item dropdown">
                                    <a class="nav-link dropdown-toggle text-white" href="/services" id="navbarDropdown2" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Services</a>
                                    <div class="dropdown-menu" aria-labelledby="navbarDropdown2">
                                        {#each services as service}
                                            <a class="dropdown-item text-dark" href={service.link}>{service.name}</a>
                                        {/each}
                                    </div>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link text-decoration-none text-white" href="/contact">Contact</a>
                                </li>
                                <li class="nav-item">
                                    <a class="btn btn-luminous-green nav-btn" href="/appointment">BOOK AN APPOINTMENT</a>
                                </li>
                            </ul>
                        </div>
                    </nav>
                </div>
            </div>
        </header>
    </div>
