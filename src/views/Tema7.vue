<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido.mb-0
      .titulo-principal__numero
        span 7
      h1 Modelo de negocio, costeo y presupuesto
    
    .row.bg01.justify-content-center.gy-3
      .col.col-10.sendFront.mt-4
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema7/img01.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Uno de los momentos más complejos para el emprendedor suele ser el establecimiento del modelo de negocio porque implica pensar en función de aspectos con los que, en la mayoría de los casos, no está familiarizado. Mayoritariamente los emprendedores se lanzan a la ejecución de las ideas pasando muy por encima de todo lo que implica el área financiera de su proyecto.

      .col.col-10.sendFront
        p.text-center Definir el modelo de negocio es responder con claridad a preguntas de gran relevancia

      .col-8.mt-4.sendFront.mb-4
        SlyderF(columnas="col-12")
          .row.justify-content-center.mb-3
            .col.col-10.p-0.m-0
              img.img-fluid(src='@/assets/curso/tema7/slyder01.png' alt='¿Qué se va a ofrecer al mercado?')
          .row.justify-content-center.mb-3
            .col.col-10.p-0.m-0
              img.img-fluid(src='@/assets/curso/tema7/slyder02.png' alt='¿Qué valor va a aportar la idea?')
          .row.justify-content-center.mb-3
            .col.col-10.p-0.m-0
              img.img-fluid(src='@/assets/curso/tema7/slyder03.png' alt='¿A quién se le va a vender?')
          .row.justify-content-center.mb-3
            .col.col-10.p-0.m-0
              img.img-fluid(src='@/assets/curso/tema7/slyder04.png' alt='¿Cómo se va a vender?')
          .row.justify-content-center.mb-3
            .col.col-10.p-0.m-0
              img.img-fluid(src='@/assets/curso/tema7/slyder05.png' alt='¿De qué forma se van a generar ingresos?')
      
      .col-10
        p Si no se tienen claras las respuestas o no se hace un correcto análisis e interpretación de ellas más allá del papel, puede que todo el proyecto se quede sin sustento real.
        p En el mundo de las 
          i.fw-bold startups
          |, una de las herramientas más comunes para definir el modelo de negocio es el Modelo 
          i.fw-bold Canvas. 
          | Este modelo recoge nueve aspectos que le permitirán al emprendedor determinar si debe lanzarse al mercado o aún no está listo para ello:

      .col-10
        img.img-fluid(src='@/assets/curso/tema7/img02.png' alt='Modelo Canvas')
        br
        p Finalmente, para conocer en más en profundidad cómo se elabora el modelo Canvas, se invita a ver el video 
          strong Cómo aplicar el modelo Canvas en el lienzo – Ejemplo práctico
          |, el cual se encuentra en el material complementario
        br
        //- Tabs
        TabsB.color-acento-contenido.mb-5
          .py-2.py-md-5(titulo="Identificación de costos en proyectos de animación" :icono="require('@/assets/curso/tema2/img-tab.svg')")
            .row.justify-content-center
              .col-10.mb-4.mb-md-0
                p En cualquier proyecto, empresa o negocio pueden diferenciarse costos directos, indirectos, relacionados con el capital, fijos y variables.
                p Con el ánimo de que el aprendiz pueda identificarlos con facilidad en su emprendimiento, a continuación, se define cada tipo de gasto en relación con los proyectos de animación:
                //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
                LineaTiempoD.color-primario
                  .row(numero="1" titulo="Costos directos")
                    .col-12
                      figure
                        img(src='@/assets/curso/tema7/linea01.png', alt='Costos directos')
                    .col-12.my-4.mb-md-0
                      p.text-small Son los que se relacionan directamente con la prestación del servicio, como por ejemplo el pago del tiempo del personal que requiera el proyecto. La manera de asignarles el valor es medir en horas hombre, la cantidad de tiempo necesario para cada una de las actividades a desarrollar por cada uno de las personas que intervengan en el desarrollo del proyecto. Por ejemplo: Coordinador general del proyecto, operador, productor, animadores, camarógrafo, escenógrafo, etc.).
                
                  .row(numero="2" titulo="Costos indirectos")
                    .col-12
                      figure
                        img(src='@/assets/curso/tema7/linea02.png', alt='Costos indirectos')
                    .col-12.my-4.mb-md-0
                      p.text-small Son los servicios complementarios que se originan como resultado de la realización del proyecto, como por ejemplo el alquiler de hardware o software, infraestructura física como workstations, servidores, nodos de render, sistema de redes, etc.

                  .row(numero="3" titulo="Costos de capital")
                    .col-12
                      figure
                        img(src='@/assets/curso/tema7/linea03.png', alt='Costos de capital')
                    .col-12.my-4.mb-md-0
                      p.text-small Son los que se producen en las inversiones realizadas, por la adquisición, acondicionamiento, mantenimiento o financiamiento de un equipo técnico, instrumentos e inmuebles necesarios para el objetivo principal del proyecto. El valor se asigna de acuerdo al valor del bien en el mercado en el caso de tener que comprarlo. Ejemplo: compra de hardware y software o acondicionamiento del mismo, compra de equipos de sonido, compra o acondicionamiento de instrumentos, licencia de Windows.

                  .row(numero="4" titulo="Costos fijos")
                    .col-12
                      figure
                        img(src='@/assets/curso/tema7/linea04.png', alt='Costos fijos')
                    .col-12.my-4.mb-md-0
                      p.text-small Son aquellos que no sufren variación cualquiera que sea la magnitud o naturaleza del proyecto, como el pago del arrendamiento de las instalaciones donde funciona el proyecto, el personal administrativo o de nómina si se ha definido una contratación mensual para uno o varios artistas. El pago del Internet, gastos financieros (contador, bancos, permisos gubernamentales) y todo lo relacionado con finanzas o registros del negocio o persona.

                  .row(numero="5" titulo="Costos variables")
                    .col-12
                      figure
                        img(src='@/assets/curso/tema7/linea05.png', alt='Costos variables')
                    .col-12.my-4.mb-md-0
                      p.text-small Dependen de las ejecuciones del proyecto y cambian de acuerdo con su magnitud y duración, como por ejemplo el número de escenas que se grabarán en una locación, un programa de animación, un plugin para usar en Maya, o un servicio en la nube para tener backups de proyectos (Dropbox o algo similar). Todo lo relacionado con las relaciones públicas y el marketing: gastos de publicidad, tarjetas de presentación, impresión de playeras, impresión de portafolios, visitas a potenciales clientes, etc
                
          .py-2.py-md-5(titulo="Definición del presupuesto" :icono="require('@/assets/curso/tema2/img-tab.svg')")
            .row.justify-content-center
              .col.col-12.mb-4.mb-md-0
                p Se trata de la organización y estimación de los recursos necesarios en cada una de las etapas y actividades del proyecto, divididos en tipos de gastos o rubros.
                p Para definir el presupuesto es fundamental e imprescindible contar con el cálculo de los costos y estar en capacidad real de estimar los ingresos, si fuera el caso.

                .row.mb-5.bg-cajon-gris
                  .col-12.col-lg-5.p-0
                    picture
                      img(src='@/assets/curso/tema7/img03.png', alt='Venta de los servicios', class='img-fluid')
                  .col-12.col-lg-7.align-self-center.p-4
                    p En el caso de la venta de los servicios, para 
                      strong determinar la asignación salarial
                      |, según los expertos, la manera más eficaz en un proyecto de animación es a través del cálculo del 
                      strong costo por hora.  
                      |El cálculo del ingreso se realiza con base en la estimación de las horas que requerirá el proyecto, multiplicado por el valor que he establecido por la hora de trabajo. Este valor se establece de acuerdo con el prorrateo de todos los gastos mensuales y el establecimiento del margen de ganancia que se espera

                p El tipo de presupuesto más usado en la formulación de proyectos es el llamado presupuesto por rubro o tipo de gasto. En la presentación de los proyectos se deben desagregar todos los gastos que requiere la ejecución de cada actividad. Esta información debe ir acompañada del cronograma financiero en donde se debe discriminar en términos monetarios, cuánto cuesta.

              .col-10.mb-4.py-2.bg-color-primario.rounded-pill.text-center
                p.mb-0 Por regla general, los proyectos de animación incluyen este tipo de costos, ver tabla 2

              .col-10
                table.tabla-presupuesto
                  thead
                    tr
                      th.principal(colspan="2") Desglose presupuesto: proyecto animado 2D
                      th.principal Desglose de costos
                    tr
                      th Arte conceptual
                      th Responsable
                      th 
                  tbody
                    tr
                      td Diseño de ambiente y utilería
                      td 
                      td 
                    tr
                      td Diseño de personajes
                      td 
                      td 
                    tr
                      td Esquemas de colores
                      td 
                      td 
                    tr
                      td Propuesta look inicial
                      td 
                      td 
                    tr
                      td Guión gráfico detallado
                      td 
                      td 
                    tr
                      td.total(colspan="2") Total arte conceptual
                      td 
                table.tabla-presupuesto
                  thead
                      th Animación y modelado
                      th Responsable
                      th 
                  tbody
                    tr
                      td Modelos de personajes
                      td 
                      td 
                    tr
                      td Plataformas de animación
                      td 
                      td 
                    tr
                      td Animación de personajes
                      td 
                      td 
                    tr
                      td Modelado final
                      td 
                      td 
                    tr
                      td.total(colspan="2") Total animación y modelado
                      td 
                table.tabla-presupuesto
                  thead
                      th Iluminación
                      th Responsable
                      th 
                  tbody
                    tr
                      td Sombras
                      td 
                      td 
                    tr
                      td Luces
                      td 
                      td 
                    tr
                      td.total(colspan="2") Total iluminación
                      td 
                table.tabla-presupuesto
                  thead
                      th Post producción
                      th Responsable
                      th 
                  tbody
                    tr
                      td Visual
                      td 
                      td 
                    tr
                      td Sonido
                      td 
                      td 
                    tr
                      td Edición final
                      td 
                      td 
                    tr
                      td.total(colspan="2") Total post producción
                      td 
                  tfoot
                    tr
                      td.total-presupuesto(colspan="2") Total del presupuesto por animación 2D
                      td
                    tr
                      td(colspan='3')
                        small Fuente: Jimena Mendezu. Crehana (2020). https://www.crehana.com/recursos/herramientas/presupuesto-animacion-2d
              .col-12.mt-4
                p Una vez que se ha definido el modelo de negocio y se sabe cómo se generan ingresos y cuáles son los costos, es necesario definir la rentabilidad, que básicamente se traduce en la diferencia positiva resultante entre los ingresos y los costos. 
</template>

<script>
export default {
  name: 'Tema7',
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
