<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p.mb-5 En este punto del componente se invita a visualizar con atención el esquema que aquí se presenta. Analice cada elemento y concepto mostrados en este y realice su propia síntesis del contenido visto. #[b ¡Adelante!]
    .row.mb-5.justify-content-center
      .col-lg-11
        figure
          img(src="@/assets/curso/sintesis.svg", alt="alt")
    .row.justify-content-center 
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis
          
</template>

<script>
export default {
  name: 'Sintesis',
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
