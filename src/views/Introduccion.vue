<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    p(data-aos="fade-right").mb-5 Se da la bienvenida al componente #[b “Conceptualización en buenas prácticas ganaderas para bovinos de carne”] y se espera que tenga una experiencia exitosa de aprendizaje, por ello, se invita a comenzar visualizando el recurso que se muestra a continuación. #[b ¡Adelante!]
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/lwnV6jceX30" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
