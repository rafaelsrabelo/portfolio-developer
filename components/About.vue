<template>
  <div class="container">
    <div class="row">
      <div class="col-sm-12 mb-2 d-block d-md-none">
        <img class="img-fluid mt-4" src="../assets/undraw_nuxt_js_0fq9.svg" />
      </div>
    <div class="col-sm-12 col-lg-6 mt-2">
      <h1 class="display-4">Hello,</h1>
      <p class="lead">
      I am {{ name }}, from Ceará, a student of systems analysis and development. I
      work as a junior web developer and I'm passionate about the front-end
      universe.
      </p>
      <h3><strong>Technologies</strong></h3>
      <div class="row">
        <a class="col" href="" target="_blank">
          <img class="img-fluid" src="../assets/html.png"/>
        </a>
        <a class="col" href="" target="_blank">
          <img class="img-fluid" src="../assets/css.png"/>
        </a>
            <a class="col" href="" target="_blank">
          <img class="img-fluid" src="../assets/bootstrap.png"/>
        </a>
        <a class="col" href="" target="_blank">
          <img class="img-fluid" src="../assets/js.png"/>
        </a>
            <a class="col" href="" target="_blank">
          <img class="img-fluid" src="../assets/vue-js.png"/>
        </a>
        <a class="col" href="" target="_blank">
          <img class="img-fluid" src="../assets/nuxt.png"/>
        </a>
    </div>
      <h3 class="mt-4"><strong>Contact me</strong></h3>
      <p class="lead">
      If you need further information, feel free to contact me on social work as
      a junior web developer and i'm passionate about the networks, or you can
      write to me instead front-end universe. {{ email }}
      </p>
      <div class="row justify-content-center mb-2">
          <a class="col-2" href="https://www.linkedin.com/in/rafaelsrabelo/" target="_blank">
            <img class="img-fluid" src="../assets/linkedin.png"/>
          </a>
          <a class="col-2" href="https://github.com/rafaelsrabelo" target="_blank">
            <img class="img-fluid" src="../assets/git.png"/>
          </a>
      </div>

    </div>
    <div class="col-lg-6 d-none d-lg-block">
      <img class="img-fluid mt-4" src="../assets/undraw_nuxt_js_0fq9.svg" />
    </div>
    </div>
  </div>
</template>


<script>
export default {
data() {
  return {
    name: "Rafael",
    email: "rafaelrabelodev@gmail.com"
  }
}
}
</script>

<style>
</style>
