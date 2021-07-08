<template>
  <section class="p-5 bg-white">
    <div class="container-lg">
      <h2>{{ SeccionProductos.titulo }}</h2>
      <p>{{ SeccionProductos.resumen }}</p>
      <div class="row g-4 text-center">
        <div class="col-md-6 col-lg-3">
          Producto
        </div>
        <div class="col-md-6 col-lg-3">
          Producto
        </div>
        <div class="col-md-6 col-lg-3">
          Producto
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "losMasVendidos",
  props: ['SeccionProductos']
}
</script>

<style scoped>

</style>
