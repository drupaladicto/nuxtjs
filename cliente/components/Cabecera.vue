<template>
  <div>
    <section class="bg-white text-dark p-5 p-lg-0 pt-lg-5 text-center text-sm-start">
      <div class="container">
        <div class="d-sm-flex align-items-center justify-content-between">
          <div class="p-2">
            <h1 id="titular-hero">A TU PUERTA</h1>
            <p class="lead">Sollicitudin litora modi aenean blandit natoque mollis lacus vehicula eligendi volutpat sodales auctor</p>
            <a href="#" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#formulario">Empieza Ahora</a>
          </div>
          <div id="img-hero" v-responsive="{ small: el => el.width <= 500 }">
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>

export default {
  name: "Cabecera",
}
</script>

<style scoped>
@media (max-width: 760px) {
  #img-hero {
    height: 300px!important;
  }
}
#titular-hero {
  font-family: 'Erica One', cursive;
  font-size: 4rem;
}

#img-hero {
  border: 2px solid;
  border-radius: 800px;
  background-image: url("~/assets/imagenes/frutas.jpg");
  width: 100%;
  height: 450px;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
</style>
