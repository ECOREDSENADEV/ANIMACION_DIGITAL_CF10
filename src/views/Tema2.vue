<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Formulación de proyectos

    .row.justify-content-center
      .col.col-10.caja.p-4.borderRounded
        p.mb-0.text-center Este apartado comprende el conocimiento de las herramientas que buscan estructurar un proceso que concluya con la consecución de recursos para llevar a cabo un proyecto de animación digital y/o la comercialización del mismo.  
      .col.col-10
        img(src='@/assets/curso/tema2/img1.jpg', alt='Formulación de proyectos')
      .col.col-10.p-4
        p.mb-0 La adquisición de estas herramientas permite concursar en las distintas convocatorias que oferta el gobierno nacional, y en otras convocatorias internacionales de carácter público y privado, por tanto el manejo de una metodología es requisito indispensable para participar en ellas y que los contenidos contemplados en las industrias creativas sean de carácter intangible y cultural por ello la información que se presenta a continuación está relacionada con la formulación de proyectos desde la perspectiva de los proyectos culturales.

    //- Tabs
    TabsB.color-acento-contenido.mb-5
      .py-2.py-md-5(titulo="Emprendimiento y emprendimiento cultural" :icono="require('@/assets/curso/tema2/img-tab.svg')")
        .row.justify-content-center
          .col.col-8.mb-4.mb-md-0
            hr.tema2
            p Antes de iniciar, es necesario comprender las diferencias entre el emprendimiento desde una visión general y el emprendimiento desde la visión cultural. 
            .bloque-texto-c.contenedor1.p-4
              i.fas.fa-quote-right.color-primario
              p.fs-5.mb-0.px-5 Según el diccionario de la Real Academia Española 
                span.fw-bold -RAE- 
                | emprendimiento viene de la palabra emprender que significa 
                span.fw-bold “acometer y comenzar una obra, un negocio, un empeño, especialmente si encierran dificultad o peligro”.
            br
            p En el uso cotidiano, el emprendimiento está relacionado con accionar recursos, inicialmente propios, en el desarrollo de unas actividades en las que se invierte el tiempo y los saberes individuales para la obtención de recursos económicos.

            .row
              .col.col-12.col-md-8.pr-3
                p El emprendimiento cultural por su parte se refiere a las acciones de tipo artístico y creativo que involucran las expresiones individuales o grupales por medio de las cuales se transmite la cultura de un lugar determinado, a la vez que crean sentido y significado, y que se realizan más que con el fin de lucro económico, con la idea de impactar a un receptor en diferentes contextos. Como ya se verificó desde el marco legal, Colombia ha regulado el quehacer artístico y creativo para que además de la creación, la difusión, la circulación, la financiación y demás componentes de esta cadena de valor, se fortalezcan y se consoliden y generen un sector económico rentable y en crecimiento permanente.
              .col.col-12.col-md-4
                img(src='@/assets/curso/tema2/img2.svg', alt='Emprendimiento cultural')

            .cajon.color-acento-contenido.p-4.mb-4
              p.px-4 El emprendimiento está relacionado con la administración de empresas como área de estudio y, aunque el éxito de un emprendimiento sí está determinado por el conocimiento de los distintos aspectos que conforman una organización, no es necesario estudiar esta carrera para tener resultados satisfactorios; 
                span.fst-italic basta con conocer las metodologías para convertir las ideas en proyectos y estos en realidades.

      .py-2.py-md-5(titulo="Proyecto cultural" :icono="require('@/assets/curso/tema2/img-tab.svg')")
        .row.justify-content-center
          .col.col-8.mb-4.mb-md-0
            hr.tema2
            p El proyecto es un formato definido para la comunicación entre un emprendedor, creativo o artista que tiene una idea o un bien intelectual o intangible, un producto o un servicio, y un financiador que tiene unos recursos económicos que puede destinar al mismo fin. El documento del proyecto contiene el detalle de las actividades, el presupuesto, el tiempo y los resultados finales; permite comprender una necesidad, un problema y ofrecer una solución. 

            .row
              .col.col-12.col-md-4
                img(src='@/assets/curso/tema2/img3.svg', alt='Proyecto cultural')
              .col.col-12.col-md-8.pr-3
                p El proyecto es un formato definido para la comunicación entre un emprendedor, creativo o artista que tiene una idea o un bien intelectual o intangible, un producto o un servicio, y un financiador que tiene unos recursos económicos que puede destinar al mismo fin. El documento del proyecto contiene el detalle de las actividades, el presupuesto, el tiempo y los resultados finales; permite comprender una necesidad, un problema y ofrecer una solución.
                p Los proyectos se formulan para planificar de manera estratégica y anticiparse a todo lo que se espera que ocurra en el proceso de generación o creación de bienes, servicios, productos e intangibles. Es el primer paso en el camino para la materialización de las ideas desde un plan de negocio. 

            .cajon.color-acento-contenido.p-4.mb-4
              p.px-4 Es importante diferenciar desde primer momento si lo que se pretende es realizar un proyecto o un plan de negocio, puesto que ambos tienen objetivos y procesos distintos, e implican métodos de trabajo diferentes, tal y como se observa en la siguiente tabla 1.

            .titulo-sexto.color-acento-contenido
              h5 Tabla 1.
              span Proyecto cultural vs Plan de negocio cultural

            table.blueTable
              thead
                tr
                  th PROYECTO CULTURAL
                  th PLAN DE NEGOCIO CULTURAL
              tbody
                tr
                  td Se ejecuta en el corto plazo, sin extenderse más allá de un año.
                  td Su ejecución es permanente y se plantea en el largo plazo.
                tr
                  td Contempla objetivos, metas e indicadores.
                  td Misión, visión, objetivos con metas e indicadores a largo plazo.
                tr
                  td Resuelve una problemática de carácter cultural.
                  td Aprovecha una oportunidad de negocio que brinda el mercado.
                tr
                  td Puede obtener utilidades económicas.
                  td Busca la sostenibilidad y rentabilidad a corto, mediano y largo plazo.
                tr
                  td Pretende la responsabilidad ciudadana permitiendo participación del estado y los particulares.
                  td Mayor autonomía en el manejo de recursos según tipo de empresa.
                tr
                  td Satisface necesidades reales.
                  td Satisface necesidades del mercado.
                tr
                  td Requiere rendición de cuentas durante y al final del proceso.
                  td Requiere estados financieros anuales.
                tr
                  td Puede requerir personería jurídica.
                  td Usualmente se conforma como una empresa comercial.
                tr
                  td Tiene presupuestos de ejecución fijos.
                  td Acepta inversiones e inyecciones de capital a lo largo del tiempo.
                tr
                  td Auditoría por el ente financiador.
                  td Auditoría de inversionistas.
                tr
                  td Ejecuta una idea precisa.
                  td Ejecuta una o varias ideas repetidamente.
                tr
                  td Ejemplos: investigación, estados del arte, programas de capacitación, rescate de situaciones de vulnerabilidad, sensibilización de problemáticas, etc.
                  td Ejemplos: Tiendas de museos, festivales, academias y escuelas, oferta de productos y servicios culturales.
            br
            p Nota. Elaboración propia a partir del Curso de formulación de proyectos culturales. Secretaría de cultura, recreación y deporte. Alcaldía Mayor de Bogotá (2021). https://formacion.scrd.gov.co 

            p Pese a que las diferencias entre ambos formatos son claras, 
              span.text-decoration-underline los proyectos audiovisuales digitales pueden tener algunas características que lo acerquen al formato de plan de negocio ya que se pueden realizar con una intención de obtener rentabilidad por los altos costos asociados. 
              | Por ejemplo, un proyecto de animación digital puede extenderse en el tiempo y obtener recursos en más de una ocasión, presentándose en diversas convocatorias o concursos. 


            .row.mt-5
              .col.col-11.bg-color-primario.borderRounded.p-4.position-relative
                p.mb-0.px-4 De la misma manera, para adaptarse a los métodos de consecución de recursos, se puede elaborar un proyecto de corto plazo que tenga por objeto generar un determinado impacto, por ejemplo, en una comunidad o un barrio.
                img.img-personas(src='@/assets/curso/tema2/img4.svg')

</template>

<script>
export default {
  name: 'Tema2',
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
