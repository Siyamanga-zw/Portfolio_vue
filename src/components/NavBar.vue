<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">S.Zweni</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link to="/"><i class="bi bi-house-add-fill"></i>Home</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/about"><i class="bi bi-file-person"></i>About</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/resume"><i class="bi bi-mortarboard-fill"></i>Resume</router-link>
            </li>

            <li class="nav-item">
              <router-link to="/project"><i class="bi bi-motherboard-fill"></i>Projects</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/testimonial"><i class="bi bi-people-fill"></i>Testimonials</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/contact"><i class="bi bi-person-lines-fill"></i>Contact</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {

};
</script>

<style scoped>
i {
  animation: flipInY;
  animation-duration: 2s;
  animation-iteration-count: infinite;
}
</style>
