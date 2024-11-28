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
  </script>

<section class="bg-accent-color-2 py-3">
    <div class="r-container">
        <div class="d-flex flex-lg-row flex-column justify-content-lg-between justify-content-center gap-3">
            <ul class="d-flex m-0 flex-lg-row flex-column justify-content-center align-items-center gap-3 text-white  text-center text-lg-start"
                style="list-style: none;">
                
                <li class="mr-2">
                    
                     <a href="tel:+447904096889">
                       Click to Call Us Now</a> 
                </li>
                <li>Email : <a href="mailto:hello@redrosecare.com">hello@redrosecare.com</a> </li>
                <li></li>
            </ul>
            
            <span class="text-white">Opening Hours : 08:00am to 07:00pm</span>
        </div>
    </div>
</section>
<section class="sticky-top bg-primary">
    <div class="r-container">
        <nav class="navbar navbar-expand-lg">
            <div class="container-fluid">
                <a class="navbar-brand" href="/">
                    <div class="logo-container">
                        <img src="image/nobglogo.png" alt="" class="img-fluid text-danger" height="75px">
                    </div>
                </a>
                <button class="navbar-toggler accent-color border-0" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <i class="fa-solid fa-bars-staggered"></i>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent ">
                    <ul class="navbar-nav mx-auto mb-2 mb-lg-0 font-2 fw-bold ">
                       
                        <li class="nav-item mx-4">
                          <a class="nav-link  me-2 text-white" href="/">Home</a>
                       </li>

                        <li class="nav-item mx-4">
                            <a class="nav-link  me-2 text-white" href="/about">About Us</a>
                        </li>

                        <!-- Add a dropdown for "Services" with items "1" and "2" -->
                        <!-- <li class="nav-item dropdown mx-4">
                            <a class="nav-link dropdown-toggle text-white" id="servicesDropdown"  data-bs-toggle="dropdown">
                                Personal Care
                            </a>
                            <ul class="dropdown-menu " aria-labelledby="servicesDropdown">
                                <li><a class="dropdown-item" href="/autism">Autism</a></li>
                                <li><a class="dropdown-item" href="/mentalhealth">Mental Health</a></li>
                            </ul>
                        </li> -->
                        <li class="dropdown">
                            <a href="javascript:void(0)" class="dropbtn">Services</a>
                            <div class="dropdown-content">
                              {#each services as service}
                                <a href={service.link}>{service.name}</a>
                              {/each}
                            </div>
                          </li>
                        <li class="nav-item mx-4">
                            <a class="nav-link  me-2 text-white" href="/contact">Contact Us</a>
                        </li>
                    </ul>
                    <a href="/appointment" class="btn button bg-accent-color" type="button">Book An
                        Appointment</a>
                </div>
            </div>
        </nav>
    </div>
</section>


<style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
  
    body {
      font-family: Arial, sans-serif;
    }
  
    /* Navbar styling */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #333;
      padding: 15px 30px;
    }
  
    .logo h1 {
      color: white;
      font-size: 1.8rem;
    }
  
    .nav-links {
      list-style-type: none;
      display: flex;
      gap: 20px;
    }
  
    .nav-links li {
      position: relative;
    }
  
    .nav-links a {
      color: white;
      text-decoration: none;
      font-size: 1rem;
      padding: 8px 16px;
      display: block;
      transition: background-color 0.3s;
    }
  
    .nav-links a:hover {
      background-color: #575757;
      border-radius: 4px;
    }
  
    /* Dropdown menu styles */
    .dropdown {
      position: relative;
      display: inline-block;
    }
  
    .dropbtn {
      background-color: #333;
      color: white;
      padding: 10px 16px;
      font-size: 1rem;
      border: none;
      cursor: pointer;
      transition: background-color 0.3s;
    }
  
    .dropbtn:hover {
      background-color: #575757;
    }
  
    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #333;
      min-width: 160px;
      z-index: 1;
      margin-top: 10px;
      border-radius: 5px;
    }
  
    .dropdown-content a {
      padding: 12px 16px;
      color: white;
      text-decoration: none;
      display: block;
    }
  
    .dropdown-content a:hover {
      background-color: #575757;
    }
  
    .dropdown:hover .dropdown-content {
      display: block;
    }
  
    .dropdown:hover .dropbtn {
      background-color: #575757;
    }
  
    /* Mobile responsiveness */
    @media (max-width: 768px) {
      .navbar {
        flex-direction: column;
        align-items: flex-start;
      }
  
      .nav-links {
        flex-direction: column;
        gap: 10px;
      }
    }
  </style>