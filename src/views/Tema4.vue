<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Hormas


    Separador
    <!-- BLOQUE  -->
    #t_4_1.titulo-segundo.color-acento-contenido
      h2 4.1 Partes de la horma



    Separador
    <!-- BLOQUE  -->
    #t_4_2.titulo-segundo.color-acento-contenido
      h2 4.2 Dimensiones de la horma



    Separador
    <!-- BLOQUE  -->
    #t_4_3.titulo-segundo.color-acento-contenido
      h2 4.3 Clasificación de las hormas


</template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
