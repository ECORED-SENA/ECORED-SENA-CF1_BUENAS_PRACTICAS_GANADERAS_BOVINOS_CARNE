<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 8
      h1 Gestión ambiental en bovinos de carne
    .row.mb-5.bg01.justify-content-center.align-items-center.mb-5
      .col-lg-7.mb-4.mb-lg-0(data-aos="fade-right")
        p #[b La ganadería es uno de los procesos productivos que más genera contaminación con efectos negativos para el medio ambiente].
        p De hecho, a nivel mundial, el sector ganadero doble propósito es reconocido por el deterioro ambiental que ocasiona. El doble propósito se concibe como un sistema de manejo pecuario en donde se debe producir, simultáneamente y en forma rentable, leche y carne en una misma explotación bovina.
        p La ganadería también va de la mano de forma directa e indirecta con:
      .col-lg-4
        img(src='@/assets/curso/tema8/1.png', style="width: 350px").m-auto
    .row.justify-content-center
      .col-12.col-lg-3.mb-4.mb-lg-0.h-100
        .bg--a-1.hoverScale2
          .row
            .col-12.paddx.mtop_1
              h4.mb-0 Talas y quemas de bosques
            .col-12.paddx.mtop_2
              p Genera impactos ambientales negativos como lo son la erosión y la compactación de los suelos.
          img(src='@/assets/curso/tema8/2.png' style='width: 550px')
      .col-12.col-lg-3.mb-4.mb-lg-0.h-100
        .bg--a-1.hoverScale2
          .row
            .col-12.paddx.mtop_3
              h4.mb-0 Quemas estacionales
            .col-12.paddx.mtop_4
              p Las quemas estacionales y la eliminación de la sucesión vegetal, si bien la ganadería está en constante cambio y evolución, como toda actividad económica puede ‘producir conservando’. 
          img(src='@/assets/curso/tema8/3.png' style='width: 550px')
      .col-12.col-lg-3.mb-4.mb-lg-0.h-100
        .bg--a-1.hoverScale2
          .row
            .col-12.paddx.mtop_5
              h4.mb-0 Producir conservando
            .col-12.paddx.mtop_6
              p Producción con una menor afectación al medio ambiente y la diversidad de fauna y flora que existe alrededor del mundo. Para lo cual #[b existen procesos que el productor puede realizar para mitigar los efectos del cambio climático.]
          img(src='@/assets/curso/tema8/4.png' style='width: 550px')
</template>

<script>
export default {
  name: 'Tema3',
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
