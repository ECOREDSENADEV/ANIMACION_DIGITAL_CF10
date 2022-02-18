<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Legislación para industrias creativas y culturales
    .row.bg01.justify-content-center
      .col-4.sendFront
        img(src='@/assets/curso/tema1/img1.png', alt='Legislación para industrias creativas y culturales')
      .col-10.sendFront.py-4.bg-white.rounded-pill.mb-4
        p.text-center.m-0 A lo largo de los años la legislación para industrias creativas y culturales se ha ido actualizando y modificando
        
    //- LineaTiempo
    LineaTiempoA.color-primario.pb-5.mb-5(:datos="datosLineaTiempoA")

    .position-relative.mt-5
      img.imgLineaTiempo.img-fluid(src='@/assets/curso/tema1/img2.png', alt='Legislación para industrias creativas y culturales')

    br
    
    .row.justify-content-center.mt-5
      .col.col-8.contenedor1.borderRounded.p-4.position-relative
        img.imgDanger(src='@/assets/curso/tema1/danger.svg')
        p.text-center Es importante resaltar que las industrias creativas comprenden los sectores que conjugan creación, producción y comercialización de bienes y servicios basados en contenidos intangibles de carácter cultural, y/o aquellos que generen protección en el marco de los derechos de autor.

    .row.my-5.justify-content-center
      .col.col-12.col-md-3    
        img.img-fluid(src='@/assets/curso/tema1/img3.jpg', alt='Economía naranja')
      .col.col-12.col-md-5    
        p En el marco legal, el Consejo de la Economía Naranja construye un programa para incentivar y aumentar las exportaciones de bienes y servicios creativos que creará un reconocimiento a las empresas que generan las mayores exportaciones en dichos sectores.
        p Este es entonces, el marco legal en el que pueden operar las empresas o profesionales que se dediquen a la producción de contenido audiovisual, donde encajan los productos de 
          span.fw-bold animación digital.
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    datosLineaTiempoA: [
      {
        ano: '1997',
        texto:
          'Reestructuración ministerial donde el Instituto Colombiano de Cultura (Colcultura) cerró para crear el Ministerio de Cultura y con este, desarrollar distintos programas para fortalecer y consolidar el sector cinematográfico del país.',
      },
      {
        ano: '2003',
        texto:
          'Se crea Ley del Cine 814 con el objetivo de consolidar y recaudar ingresos para la internacionalización del cine nacional por medio de estímulos tributarios en el sector privado. Su intención consistía en dinamizar e impulsar producciones para garantizar un flujo de recursos y de esta forma trabajar junto con la Comisión Fílmica Colombiana en el fomento de las producciones.',
      },
      {
        ano: '2012',
        texto:
          'Se crea la Ley 1556 que propone una contraprestación del 40% del valor de los gastos realizados en el país por concepto de servicios cinematográficos y del 20% del valor de los gastos en hotelería, alimentación y transporte a las empresas que celebren contratos con Filmación Colombia y realicen las producciones cinematográficas total o parcialmente en el territorio colombiano.',
      },
      {
        ano: '2017',
        texto:
          'se crea la Ley 1834 de 2017 que tiene como objeto desarrollar, fomentar, incentivar y proteger las industrias creativas. Estas son entendidas como aquellas industrias que generan valor, en razón de sus bienes y servicios, los cuales se fundamentan en la propiedad intelectual.',
      },
      {
        ano: '2020',
        texto:
          'A través del Decreto 474 la ley 1556 se extiende por 10 años más y se amplían los beneficios de esta norma a otros géneros audiovisuales como series, videos musicales, proyectos de animación y videojuegos, realización audiovisual publicitaria y series de contenidos cortos para web. Igualmente se ofrece el Certificado de Inversión Audiovisual - CINA, un incentivo tributario que busca apalancar proyectos de inversión de productores extranjeros y que pretende posicionar a Colombia como el nuevo hub de la industria audiovisual en América Latina.',
      },
    ],
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
