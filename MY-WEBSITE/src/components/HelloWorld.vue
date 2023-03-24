<script>

export default {
  data() {

  },
  methods: {

  }
}

</script>

<template>
  <body id="page-top">
    <!-- Navigation-->
    <nav class="navbar navbar-expand-lg navbar-light fixed-top" id="mainNav">
      <div class="container px-4 px-lg-5">
        <a class="navbar-brand" href="#page-top">Alby Schianni</a>
        <button class="navbar-toggler navbar-toggler-right" type="button" data-bs-toggle="collapse"
          data-bs-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false"
          aria-label="Toggle navigation">
          Menu
          <i class="fas fa-bars"></i>
        </button>
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
            <h2 class="text-white-as mx-auto mt-2 mb-5">I'm Alberto, a web developer and this is my website</h2>
          </div>
        </div>
      </div>
    </header>
    <!-- About-->
    <section class="about-section text-center" id="about">
      <div class="container px-4 px-lg-5">
        <div class="row gx-4 gx-lg-5 justify-content-center">
          <div class="col-lg-12 flex-meDev">
            <img class="img-me" src="../assets/me-dev.jpg" alt="..." />
            <div>
              <h2 class="text-white mb-4">Full Stack Web developer</h2>
              <p class="text-white-50">
                Grayscale is a free Bootstrap theme created by Start Bootstrap. It can be yours right now, simply download
                the template on
                <a href="https://startbootstrap.com/theme/grayscale/">the preview page.</a>
                The theme is open source, and you can use it for any purpose, personal or commercial.
              </p>
            </div>

          </div>
        </div>

      </div>
    </section>
    <!-- Projects-->
    <section class="projects-section bg-light" id="projects">
      <div class="container px-4 px-lg-5">
        <!-- Featured Project Row-->
        <div class="row gx-0 mb-4 mb-lg-5 align-items-center">
          <div class="col-xl-8 col-lg-7"><img class="img-fluid mb-3 mb-lg-0" src="assets/img/bg-masthead.jpg" alt="..." />
          </div>
          <div class="col-xl-4 col-lg-5">
            <div class="featured-text text-center text-lg-left">
              <h4>Shoreline</h4>
              <p class="text-black-50 mb-0">Grayscale is open source and MIT licensed. This means you can use it for any
                project - even commercial projects! Download it, customize it, and publish your website!</p>
            </div>
          </div>
        </div>
        <!-- Project One Row-->
        <div class="row gx-0 mb-5 mb-lg-0 justify-content-center">
          <div class="col-lg-6"><img class="img-fluid" src="assets/img/demo-image-01.jpg" alt="..." /></div>
          <div class="col-lg-6">
            <div class="bg-black text-center h-100 project">
              <div class="d-flex h-100">
                <div class="project-text w-100 my-auto text-center text-lg-left">
                  <h4 class="text-white">Misty</h4>
                  <p class="mb-0 text-white-50">An example of where you can put an image of a project, or anything else,
                    along with a description.</p>
                  <hr class="d-none d-lg-block mb-0 ms-0" />
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- Project Two Row-->
        <div class="row gx-0 justify-content-center">
          <div class="col-lg-6"><img class="img-fluid" src="assets/img/demo-image-02.jpg" alt="..." /></div>
          <div class="col-lg-6 order-lg-first">
            <div class="bg-black text-center h-100 project">
              <div class="d-flex h-100">
                <div class="project-text w-100 my-auto text-center text-lg-right">
                  <h4 class="text-white">Mountains</h4>
                  <p class="mb-0 text-white-50">Another example of a project with its respective description. These
                    sections work well responsively as well, try this theme on a small screen!</p>
                  <hr class="d-none d-lg-block mb-0 me-0" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact-->
    <section class="contact-section bg-black padding-footer" id="contact">
      <div class="container px-4 px-lg-5">
        <div class="row gx-4 gx-lg-5 d-flex justify-content-center">

          <div class="col-md-8 mb-3 mb-md-0">
            <div class="card py-4 h-100">
              <div class="card-body text-center">
                <i class="fas fa-envelope text-primary mb-2"></i>
                <h3 class="text-uppercase m-0">Email</h3>
                <hr class="my-4 mx-auto" />
                <div>If you need to contact me, you can write to the email below.</div>
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

          <a class="mx-2" href="https://www.linkedin.com/in/alberto-schianni-513610206/"><font-awesome-icon
              :icon="['fab', 'linkedin']" size="xl" /></a>
          <a class="mx-2" href="https://github.com/albyschianni"><font-awesome-icon :icon="['fab', 'github']"
              size="xl" /></a>
          <a class="mx-2" href="https://www.instagram.com/albyschianni/?next=%2F"><font-awesome-icon
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
