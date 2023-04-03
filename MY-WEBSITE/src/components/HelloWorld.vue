<script>

export default {
  name: 'MyButton',
  data() {
    return {
      showDropdown: false
    }
  },

}

</script>

<template>
  <body id="page-top">
    <!-- Navigation-->
    <nav class="navbar navbar-expand-lg navbar-light fixed-top" id="mainNav">
      <div class="container px-4 px-lg-5 d-flex flex-nowrap">
        <a class="navbar-brand" href="#page-top"> <img class="size-logo" src="../assets/alby_logoLisa2.png" alt=""></a>

        <div class="dropdown">
          <button class="ms-button btn btn-secondary dropdown-toggle " type="button" data-bs-toggle="dropdown"
            aria-expanded="false">
            Menu
          </button>
          <ul class="dropdown-menu">
            <li><a class="ms-aButton" href="#about">About</a></li>
            <li><a class="ms-aButton" href="#projects">Projects</a></li>
            <li><a class="ms-aButton" href="#contact">Contact</a></li>
          </ul>
        </div>

        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
            <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
            <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- Masthead-->
    <header class="masthead">
      <div class="container px-4 px-lg-5 d-flex h-100 align-items-center justify-content-center">
        <div class="d-flex justify-content-center">
          <div class="text-center">
            <h1 class="mx-auto my-0 text-uppercase">Web Developer</h1>
            <h2 class="text-white-as mx-auto mt-2 mb-5"></h2>
          </div>
        </div>
      </div>
    </header>
    <!-- About-->
    <section class="about-section text-center" id="about">
      <div class="container px-4 px-lg-5">
        <div class="row gx-4 gx-lg-5 justify-content-center">
          <div class="col-lg-12 flex-meDev">
            <img class="img-me" src="../assets/myself.jpg" alt="..." />
            <div class="div-name">
              <h2 class="text-white mb-4 div-ms-medium ">ALBERTO SCHIANNI</h2>
              <p class="text-white-50 text-start ms-text-style p-ms-medium">
                Hi, I'm 23 Italian guy. <br>
                After my graduation in Communication Media & Advertising I decided to study Web Development
                driven by love for technology & innovation. <br>
                During my studies I've learned many languages and framework:
              </p>
              <div class="d-flex justify-content-around">
                <div>
                  <h4 class="h4-ms-medium" style="color: white;">FRONT-END</h4>
                  <div class="d-flex align-items-center gap-logos">
                    <ul class="text-start">
                      <li class="li-ms-medium">HTML </li>
                      <li class="li-ms-medium">CSS </li>
                      <li class="li-ms-medium">JAVASCRIPT </li>
                      <li class="li-ms-medium">VUE JS </li>
                    </ul>

                  </div>
                </div>
                <div>
                  <h4 class="h4-ms-medium" style="color: white;">BACK-END</h4>
                  <div class="d-flex align-items-center gap-logos">
                    <ul class="text-start">
                      <li class="li-ms-medium">PHP </li>
                      <li class="li-ms-medium">MYSQL </li>
                      <li class="li-ms-medium">LARAVEL </li>
                    </ul>
                  </div>
                </div>
              </div>
              <div class="ms-text-style text-start div-cv-medium" style="margin-top: 30px;">
                For more info:
                <a href="https://drive.google.com/drive/folders/1y_l-wsDdOdKuhxG1bb5UIL8Wf-suMuLW?usp=share_link"
                  style="text-decoration: none; color: white;">
                  <font-awesome-icon :icon="['fas', 'file-invoice']" size="lg" />
                  Download CV
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- SECTION PROJECTS -->

    <section class="projects-section bg-light project-two-line" id="projects">
      <div class="container px-4 px-lg-5">
        <h1 class="h1-projects">
          PROJECTS
        </h1>
        <div class="row gx-0 mb-4 mb-lg-5 align-items-center">
          <div class="col-xl-8 col-lg-7"><img class="img-fluid mb-3 mb-lg-0" src="../assets/spotify.png" alt="..." />
          </div>
          <div class="col-xl-4 col-lg-5">
            <div class="featured-text text-center text-lg-left">
              <h4>Airbnb Clone <br>(Front-end & Back-end)</h4>
              <p class="text-black-50 mb-0">
                With my team we created an Airbnn replica with many function: full CRUD for data, an advanced
                research with some filter (TomTom API for location), safe routes inside the app, register & login section,
                possibility to simulate payment with Braintree, dedicate page for messages from users and statistics to
                check the apartment'views. <br>
                - VUE JS / LARAVEL (JAVASCRIPT & PHP)
              </p>
            </div>
          </div>
        </div>

        <div class="row gx-0 mb-4 mb-lg-5 align-items-center">
          <div class="col-xl-4 col-lg-5">
            <div class="featured-text-2 text-center text-lg-left">
              <h4>Website Landing Page <br>(Front-end)</h4>
              <p class="text-black-50 mb-0">
                Full Landing Page graphic, simulation of a website divided in many sections. Created with VUE JS using
                components structure to mantain the code.
              </p>
            </div>
          </div>
          <div class="col-xl-8 col-lg-7 image-carousel-ms">
            <img class="img-fluid mb-3 mb-lg-0" src="../assets/exsite.png" alt="..." />
          </div>
        </div>

        <div class="row gx-0 mb-4 mb-lg-5 align-items-center">
          <div class="col-xl-8 col-lg-7"><img class="img-fluid mb-3 mb-lg-0" src="../assets/spotify.png" alt="..." />
          </div>
          <div class="col-xl-4 col-lg-5">
            <div class="featured-text text-center text-lg-left">
              <h4>Spotify <br>(Front-end)</h4>
              <p class="text-black-50 mb-0">
                Spotify Homepage, replica inspired by famous Music Webapp, full CSS & HTML structure responsive on many
                size/devices.
              </p>
            </div>
          </div>
        </div>

        <div class="row gx-0 mb-4 mb-lg-5 align-items-center">

          <div class="col-xl-4 col-lg-5">
            <div class="featured-text-2 text-center text-lg-left">
              <h4>Netflix <br>(Front-end / API)</h4>
              <p class="text-black-50 mb-0">
                Netflix Homepage, replica inspired by famous Streaming Webapp created with VUE JS for the components
                structure. Inside the cards it's possible to view some data (Title, Overview,rating..) generated by using
                "ThemovieDB" API and with the search button you can search inside the Whole catalog the movie you prefer.
              </p>
            </div>
          </div>
          <div class="col-xl-8 col-lg-7"><img class="img-fluid mb-3 mb-lg-0" src="../assets/netflix.png" alt="..." />
          </div>
        </div>

        <div class="row gx-0 mb-4 mb-lg-5 align-items-center">
          <div class="col-xl-8 col-lg-7"><img class="img-fluid mb-3 mb-lg-0" src="../assets/whatsapp.png" alt="..." />
          </div>
          <div class="col-xl-4 col-lg-5">
            <div class="featured-text text-center text-lg-left">
              <h4>Whatsapp <br>(Front-end)</h4>
              <p class="text-black-50 mb-0">
                Whatsapp Chat-page, replica inspired by famous messaging Webapp created with HTML CSS & JS, you can select
                the chat you prefer and write a message, the app will respond to you with a default message.
              </p>
            </div>
          </div>
        </div>

      </div>
    </section>

    <!-- SECTION PROJECTS 2-->

    <section class="projects-section bg-light project-one-line" id="projects">
      <div class="container px-4 px-lg-5">
        <h1 class="h1-projects">
          PROJECTS
        </h1>
        <div class="row gx-0 mb-4 mb-lg-5 align-items-center">

          <div class="col-xl-4 col-lg-5">
            <div class="featured-text text-center text-lg-left">
              <h4>Airbnb Clone <br>(Front-end & Back-end)</h4>
              <p class="text-black-50 mb-4">
                With my team we created an Airbnn replica with many function: full CRUD for data, an advanced
                research with some filter (TomTom API for location), safe routes inside the app, register & login section,
                possibility to simulate payment with Braintree, dedicate page for messages from users and statistics to
                check the apartment'views. <br>
                - VUE JS / LARAVEL (JAVASCRIPT & PHP)
              </p>
            </div>
            <div class="col-xl-8 col-lg-7">
              <img class="img-fluid mb-3 mb-lg-0" src="../assets/spotify.png" alt="..." />
            </div>
          </div>
        </div>

        <div class="row gx-0 mb-4 mb-lg-5 align-items-center">
          <div class="col-xl-4 col-lg-5">
            <div class="featured-text-2 text-center text-lg-left">
              <h4>Website Landing Page <br>(Front-end)</h4>
              <p class="text-black-50 mb-4">
                Full Landing Page graphic, simulation of a website divided in many sections. Created with VUE JS using
                components structure to mantain the code.
              </p>
            </div>
          </div>
          <div class="col-xl-8 col-lg-7 image-carousel-ms">
            <img class="img-fluid mb-3 mb-lg-0" src="../assets/exsite.png" alt="..." />
          </div>
        </div>

        <div class="row gx-0 mb-4 mb-lg-5 align-items-center">
          <div class="col-xl-4 col-lg-5">
            <div class="featured-text text-center text-lg-left">
              <h4>Spotify <br>(Front-end)</h4>
              <p class="text-black-50 mb-4">
                Spotify Homepage, replica inspired by famous Music Webapp, full CSS & HTML structure responsive on many
                size/devices.
              </p>
            </div>
            <div class="col-xl-8 col-lg-7">
              <img class="img-fluid mb-3 mb-lg-0" src="../assets/spotify.png" alt="..." />
            </div>
          </div>
        </div>

        <div class="row gx-0 mb-4 mb-lg-5 align-items-center">
          <div class="col-xl-4 col-lg-5">
            <div class="featured-text-2 text-center text-lg-left">
              <h4>Netflix <br>(Front-end / API)</h4>
              <p class="text-black-50 mb-4">
                Netflix Homepage, replica inspired by famous Streaming Webapp created with VUE JS for the components
                structure. Inside the cards it's possible to view some data (Title, Overview,rating..) generated by
                using
                "ThemovieDB" API and with the search button you can search inside the Whole catalog the movie you
                prefer.
              </p>
            </div>
            <div class="col-xl-8 col-lg-7">
              <img class="img-fluid mb-3 mb-lg-0" src="../assets/netflix.png" alt="..." />
            </div>
          </div>
        </div>

        <div class="row gx-0 mb-4 mb-lg-5 align-items-center">
          <div class="col-xl-4 col-lg-5">
            <div class="featured-text text-center text-lg-left">
              <h4>Whatsapp <br>(Front-end)</h4>
              <p class="text-black-50 mb-4">
                Whatsapp Chat-page, replica inspired by famous messaging Webapp created with HTML CSS & JS, you can select
                the chat you prefer and write a message, the app will respond to you with a default message.
              </p>
            </div>
            <div class="col-xl-8 col-lg-7">
              <img class="img-fluid mb-3 mb-lg-0" src="../assets/whatsapp.png" alt="..." />
            </div>
          </div>
        </div>

      </div>
    </section>

    <!-- Contact-->
    <section class="contact-section bg-black padding-footer" id="contact">
      <div class="container px-4 px-lg-5">
        <div class="row gx-4 gx-lg-5 d-flex justify-content-center">

          <div class="col-md-7 mb-3 mb-md-0">
            <div class="card py-4 h-100" style="background-color: #161617;">
              <div class="card-body text-center">
                <i class="fas fa-envelope text-primary mb-2"></i>
                <h3 class="text-uppercase m-0" style="color: white;">Email</h3>
                <hr class="my-4 mx-auto color-hr" />
                <div style="color: white;">If you need to contact me, you can write to the email below.</div>
                <div class="small text-black-50 margin-email"><a
                    href="mailto:alberto.schianni@gmail.com">alberto.schianni@gmail.com</a></div>
              </div>
            </div>
          </div>

        </div>
        <div class="d-flex justify-content-center text-profile-ms ">
          My Social Profile
        </div>
        <hr class="my-4 mx-auto color-hr" />
        <div class="social d-flex justify-content-center">

          <a class="mx-2" href="https://www.linkedin.com/in/alberto-schianni-513610206/"
            target="_blank"><font-awesome-icon :icon="['fab', 'linkedin']" size="xl" /></a>
          <a class="mx-2" href="https://github.com/albyschianni" target="_blank"><font-awesome-icon
              :icon="['fab', 'github']" size="xl" /></a>
          <a class="mx-2" href="https://www.instagram.com/albyschianni/?next=%2F" target="_blank"><font-awesome-icon
              :icon="['fab', 'instagram']" size="xl" /></a>
        </div>
      </div>
    </section>

  </body>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
