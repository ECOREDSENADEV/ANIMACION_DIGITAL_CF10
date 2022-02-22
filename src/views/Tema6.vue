<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Seguimiento o monitoreo de proyectos

    .row.justify-content-center.gy-5
      .col.col-10
        .bloque-texto-d.color-secundario.p-4
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
            h3.text-regular Esta fase comprende los procesos necesarios para realizar el seguimiento, revisión y monitorización del progreso de proyecto. Se concibe como el medio para detectar desviaciones con la máxima premura posible, y así identificar las áreas en las que puede ser requerido un cambio en la planificación y un plan de contingencias. La etapa de seguimiento y control se encuentra naturalmente asociada a la de ejecución, de la que no puede concebirse de forma separada por su importancia y valor crítico.
            i.fas.fa-quote-right
          .bloque-texto-d__autor
            .h5.mb-0 Guía OBS Online, Business School, 2019
      
      .col.col-10.col-lg-4
        picture
          img(src='@/assets/curso/tema6/img01.png', alt='Actividades necesarias', class='img-fluid')
      
      .col.col-10.col-lg-6
        p Las actividades necesarias para esta etapa son las siguientes
        ol.lista-ol--cuadro
          li
            .lista-ol--cuadro__vineta
              span 1
            | Actualización y seguimiento de los instrumentos de gestión de proyecto
          li
            .lista-ol--cuadro__vineta
              span 2
            | Definición y establecimiento de los indicadores clave de gestión
          li
            .lista-ol--cuadro__vineta
              span 3
            | Monitorización de los indicadores clave de gestión
          li
            .lista-ol--cuadro__vineta
              span 4
            | Planificación y puesta en marcha de acciones correctoras
          li
            .lista-ol--cuadro__vineta
              span 5
            | Creación de un plan de contingencias

      .col.col-10
        p Los documentos relevantes durante esta etapa son el Checklist y revisiones de cada fase como el plan de gestión del riesgo, la comunicación de desviaciones detectadas, comunicación de acciones correctoras o modificaciones a aplicar y su plazo      

        //- Tabs
        TabsB.color-acento-contenido.mb-5
          .py-2.py-md-5(titulo="Métodos para el seguimiento de proyectos" :icono="require('@/assets/curso/tema2/img-tab.svg')")
            .row.justify-content-center.gy-5
              .col.col-10.mb-4.mb-md-0
                picture
                  img(src='@/assets/curso/tema6/tab01.png', alt='Métodos para el seguimiento de proyectos', class='img-fluid')  
              .col.col-12.mb-4.mb-md-0
                p Las metodologías más usadas para el seguimiento de proyectos son el Diagrama de Gantt, Pert, CPM o el Método de la Cadena Crítica.
                p Sin embargo, muchas aplicaciones para la gestión de proyectos están basadas en estas metodologías o permiten que se adapten, por lo que la contratación de un servicio de pago o gratuito, actualmente facilita el seguimiento de los procesos, incluso en equipos que trabajan exclusivamente de manera virtual. Dar una opinión sobre cuál de estas herramientas es mejor, es complejo y cada usuario o equipo debe encontrar la que mejor se adapte a sus necesidades.
 
              .col.col-12.contenedor1.borderRounded.my-4.p-4.text-center
                p.mb-0 Para ampliar la información sobre esta temática, se invita a visitar en el material complementario mediante los siguientes recursos:
              
              .col.col-12.mb-4.mb-md-0
                ol.lista-ol--cuadro
                  li
                    .lista-ol--cuadro__vineta
                      span 1
                    | Cómo realizar el seguimiento de un proyecto – Metodologías de seguimiento y control.
                  li
                    .lista-ol--cuadro__vineta
                      span 2
                    | Diagrama de Gantt – Administración de proyectos.
                  li
                    .lista-ol--cuadro__vineta
                      span 3
                    | 31 herramientas de gestión de proyectos destacadas para 2022

          .py-2.py-md-5(titulo="Definición y establecimiento de los indicadores" :icono="require('@/assets/curso/tema2/img-tab.svg')")
            .row.justify-content-center.gy-5
              .col.col-10.mb-4.mb-md-0
                picture
                  img(src='@/assets/curso/tema6/tab02.png', alt='Definición y establecimiento de los indicadores', class='img-fluid')  
              .col.col-12.mb-4.mb-md-0
                p Los indicadores son herramientas que aportan información medible sobre los aspectos más relevantes de un proyecto.

                //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
                .cajon.color-primario.p-4.mb-4
                  p Un Indicador es una expresión cualitativa o cuantitativa observable que permite describir características, comportamientos o fenómenos de la realidad a través de la evolución de una variable o el establecimiento de una relación entre variables que, comparadas con periodos anteriores, o frente a una meta o compromiso, permite evaluar el desempeño y su evolución en el tiempo. Los indicadores sirven para establecer el logro y el cumplimiento de la misión, objetivos, metas, programas o políticas de un determinado proceso o estrategia, por esto podemos decir que son, ante todo, la información que agrega valor y no simplemente un dato.

                p Los indicadores permiten evidenciar el nivel de cumplimiento acerca de lo que está haciendo la organización y sobre los efectos de sus actividades y según el Departamento Administrativo de la Función Pública (2012), en la guía para indicadores de gestión señala a través de la medición de aspectos tales como: talento humano, presupuesto, planta y equipos; cargas de trabajo, número de personas requeridas para realizar una actividad. Resultados como ciudadanos atendidos, oficios respondidos, ejecución del cronograma, niños vacunados, kilómetros construidos, etc.

              .row.mb-5
                .col-md-6.col-lg.mb-5.mb-lg-0
                  .tarjeta-avatar
                    img(src='@/assets/curso/tema6/impacto.png' alt='Impacto')
                    .tarjeta.bg-color-primario
                      .text-black.p-4
                        h2.text-center Impacto
                        p.text-center de los productos y/o servicios, tales como enfermedades prevenidas, impuestos recolectados, niveles de seguridad laboral alcanzados.

                .col-md-6.col-lg.mb-5.mb-lg-0
                  .tarjeta-avatar
                    img(src='@/assets/curso/tema6/productividad.png' alt='Impacto')
                    .tarjeta.bg-color-primario
                      .text-black.p-4
                        h2.text-center Productividad
                        p.text-center como casos atendidos por profesionales, solicitudes procesadas por persona, llamadas de emergencia atendidas.

                .col-md-6.col-lg.mb-5.mb-lg-0
                  .tarjeta-avatar
                    img(src='@/assets/curso/tema6/impacto.png' alt='Impacto')
                    .tarjeta.bg-color-primario
                      .text-black.p-4
                        h2.text-center Satisfacción del usuario
                        p.text-center como el número de quejas recibidas, resultados de las encuestas, utilización de procesos participativos, visitas a los clientes.


</template>

<script>
export default {
  name: 'Tema6',
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
