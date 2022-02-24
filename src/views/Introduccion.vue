<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.bgIntro
      .col.col-12.col-lg-7.p-0
        .row.justify-content-center.my-4
          .col-10
            p Durante el siguiente componente formativo, se abordan los contenidos que permiten introducirse en las temáticas relativas a la legislación colombiana para las industrias culturales y creativas, aprovechando las disposiciones de ley y programas de ayudas de los que se dispone; igualmente se podrá entender la importancia de la formulación de proyectos, las metodologías para la formulación y gestión, así como las convocatorias de ayudas y fuentes de financiación. 
          .col-10.bg-white.py-3.px-5
            p.mb-0 Posteriormente, se obtendrá la información que posibilite la elaboración de la lista de costos y presupuestos para que finalmente se puedan integrar los productos en estrategias digitales que consigan difusión, competitividad, visibilidad o algún otro proceso necesario que contribuya a la conversión digital de las empresas del país.
      .col.col-12.col-lg-5.p-0
        img(src='@/assets/curso/introduccion/introduccion.jpg', alt='Introducción')
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
