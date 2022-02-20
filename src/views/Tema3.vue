<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 ¿Cómo realizar proyectos?

    .row.bg01.justify-content-center
      .col-8.sendFront.py-4.bg-white.rounded-pill.m-4
        p.text-center.m-0 Para formular un proyecto es necesario formular y responder a las siguientes preguntas:
      
      .col-8.mt-4.sendFront
        SlyderF(columnas="col-12")
          .row.justify-content-center.mb-3
            .col.col-10.p-0.m-0
              img.img-fluid(src='@/assets/curso/tema3/slyder01.png' alt='¿Qué se va a hacer y para qué?')
          .row.justify-content-center.mb-3
            .col.col-10.p-0.m-0
              img.img-fluid(src='@/assets/curso/tema3/slyder02.png' alt='¿Qué es necesario hacer?')
          .row.justify-content-center.mb-3
            .col.col-10.p-0.m-0
              img.img-fluid(src='@/assets/curso/tema3/slyder03.png' alt='¿Cómo se va a hacer? ')
          .row.justify-content-center.mb-3
            .col.col-10.p-0.m-0
              img.img-fluid(src='@/assets/curso/tema3/slyder04.png' alt='¿En qué tiempo se va a hacer?')
          .row.justify-content-center.mb-3
            .col.col-10.p-0.m-0
              img.img-fluid(src='@/assets/curso/tema3/slyder05.png' alt='¿Con qué costos?')
          .row.justify-content-center.mb-3
            .col.col-10.p-0.m-0
              img.img-fluid(src='@/assets/curso/tema3/slyder06.png' alt='¿Quién lo va a hacer?')

      .col-8.mt-4.sendFront
        p A partir de esta información, todos los proyectos tienen un ciclo de vida estandarizado que se refiere al orden de las etapas por las que transita desde su inicio hasta el fin, ver figura 1.
        br
        .titulo-sexto.color-acento-contenido
          h5 Figura 1.
          span Etapas del ciclo de vida del proyecto

        img.img-fluid(src='@/assets/curso/tema3/etapas.png' alt='Etapas del ciclo de vida del proyecto')
        br
        p.my-3 El ciclo de vida de un proyecto inicia con un proceso de 
          strong identificación 
          | que comprende el análisis de los involucrados, los problemas, los objetivos y de las estrategias. Seguidamente, debe elaborarse una 
          strong valoración de factibilidad, 
          | de implicaciones financieras, de sostenibilidad y de factores de éxito. Sólo luego de este proceso es posible adentrarse en la etapa de la 
          strong formulación 
          | del proyecto, que debe contar con una estructura lógica. Posteriormente inicia una fase de 
          strong negociaciones 
          | en las que se evalúa la financiación del proyecto, se buscan y se realizan convenios y definen la etapa de 
          strong ejecución, 
          | es decir, el plan operativo, y el plan de acción. Finalmente, siempre deben existir actividades de 
          strong monitoreo o seguimiento y evaluación 
          | de eficiencia, efectividad e impacto de las iniciativas culturales.

        .cajon.color-primario.p-4.mb-4
          p La decisión de realizar un proyecto tiene que ver con una motivación, inquietud, oportunidad o suceso que provoca en el autor un interés tal, como para iniciar el proceso de consecución de recursos que permitirán su ejecución. Los proyectos normalmente están condicionados por el contexto económico, social e institucional que determinan el alcance que tendrán.

    //- Tabs
    TabsB.color-acento-contenido.mb-5
      .py-2.py-md-5(titulo="Etapas de un proyecto" :icono="require('@/assets/curso/tema2/img-tab.svg')")
        .row.justify-content-center
          .col.col-10.mb-4.mb-md-0
            p Para el caso de un proyecto audiovisual, este proceso se refiere a la búsqueda, definición y gestión de recursos financieros, materiales y de talento humano necesarios para transformar una idea concebida o adquirida, en un producto o contenido audiovisual.
            br
            p Paralelo al ciclo de vida de un proyecto genérico, las etapas de un proyecto o producción audiovisual son las siguientes:

            figure
              .video
                iframe(width='560' height='315' src='https://www.youtube.com/embed/2L91WMqw96A' title='YouTube video player' frameborder='0' allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture' allowfullscreen)

          .col.col-10.contenedor1.borderRounded.my-4.p-4
            p A continuación, se presentan los elementos, ordenados según fases, que según el Instituto Latinoamericano de Planificación Económica y Social (ILPES), de la FAO y de otras instituciones y autores, se consideran básicos en la formulación de proyectos, independiente del área social, económica o educativa al que pertenezca:
          .col.col-10.my-4.mb-md-0
            SlyderB.mb-5.p-1(:datos="datosSlyder")

      .py-2.py-md-5(titulo="Metodologías para la formulación de proyectos " :icono="require('@/assets/curso/tema2/img-tab.svg')")
        .row.justify-content-center
          .col.col-10.mb-4.mb-md-0
            p Además del ciclo de vida, para abordar las problemáticas desde la perspectiva de proyecto, existen otros métodos o metodologías para asumir las acciones a desarrollar. Cada metodología prioriza los aspectos en los que se enfocará el desarrollo del proyecto, pero todas persiguen alcanzar resultados satisfactorios. La elección de la metodología es uno de los aspectos más importantes en la formulación de proyectos, ya que de la correcta ejecución de cada una de sus etapas, se conseguirán o no, los objetivos previstos.
            br
            p Se verá a continuación un referente de las más utilizadas a través del siguiente vídeo:

            figure
              .video
                iframe(width='560' height='315' src='https://www.youtube.com/embed/2L91WMqw96A' title='YouTube video player' frameborder='0' allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture' allowfullscreen)
            br

          .col.col-8.cajonFEE9CC.borderRounded.my-4.p-4
            p En el caso de 
              span.text-decoration-underline la creación de los contenidos 
              | o piezas de 
              span.text-decoration-underline animación digital 
              | que 
              span.text-decoration-underline son en sí mismos un proyecto tecnológico (videojuego, película) 
              | o que sirven como componentes de ellos (aplicación, web, etc.), es necesario evaluar el uso de las metodologías para la gestión de proyectos digitales o de software.
          
          .col.col-10.mb-4.mb-md-0
            p La compañía Wrike ha categorizado en su página web las principales metodologías para la gestión de proyectos de la siguiente manera

          .tarjeta.bgLineaTiempo.p-4.mb-5
            //- LineaTiempoC debe ir acompañado de una de una de estas clases => 
            //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
            //- text-small se usa para que los títulos sean mas pequeños
            LineaTiempoC(text-small)
              .row(titulo="Secuencial").justify-content-center
                .col-10.bg-white.mb-4.p-4
                  span.fw-bold Metodologías secuenciales tradicionales
                  p
                  ul.lista-ul--color
                    li 
                      i.lista-ul__vineta
                      | Metodología de gestión de proyectos en cascada.
                    li 
                      i.lista-ul__vineta
                      | Método de la ruta crítica (CPM en inglés).
                    li 
                      i.lista-ul__vineta
                      | Gestión de proyectos de cadena crítica (CCPM en inglés).
                .col-10.mb-4.mb-md-0
                  img(src='@/assets/curso/tema3/linea-secuencial.png', alt='Metodologías secuenciales tradicionales')

              .row(titulo="Agile").justify-content-center
                .col-10.bg-white.mb-4.p-4
                  span.fw-bold Metodologías Agile
                  p
                  ul.lista-ul--color
                    li 
                      i.lista-ul__vineta
                      | Metodología de gestión de proyectos Agile.
                    li 
                      i.lista-ul__vineta
                      | Scrum.
                    li 
                      i.lista-ul__vineta
                      | Kanban.
                    li 
                      i.lista-ul__vineta
                      | Extreme Programming (XP).
                    li 
                      i.lista-ul__vineta
                      | Marco de proyectos adaptativo (APF, por sus siglas en inglés).
                .col-10.mb-4.mb-md-0
                  img(src='@/assets/curso/tema3/linea-agile.png', alt='Metodologías Agile')
          
              .row(titulo="Cambio").justify-content-center
                .col-10.bg-white.mb-4.p-4
                  span.fw-bold Metodologías de gestión del cambio
                  p
                  ul.lista-ul--color
                    li 
                      i.lista-ul__vineta
                      | Metodología de la cadena de eventos (ECM, por sus siglas en inglés).
                    li 
                      i.lista-ul__vineta
                      | Gestión de proyectos extrema (XPM, por sus siglas en inglés).
                .col-10.mb-4.mb-md-0
                  img(src='@/assets/curso/tema3/linea-cambio.png', alt='Metodologías de gestión del cambio')
          
              .row(titulo="Proceso").justify-content-center
                .col-10.bg-white.mb-4.p-4
                  span.fw-bold Metodologías basadas en el proceso
                  p
                  ul.lista-ul--color
                    li 
                      i.lista-ul__vineta
                      | Lean.
                    li 
                      i.lista-ul__vineta
                      | Six Sigma.
                    li 
                      i.lista-ul__vineta
                      | Lean Six-Sigma.
                    li 
                      i.lista-ul__vineta
                      | Gestión de proyectos basada en procesos.
                .col-10.mb-4.mb-md-0
                  img(src='@/assets/curso/tema3/linea-proceso.png', alt='Metodologías basadas en el proceso')
          
              .row(titulo="Otras").justify-content-center
                .col-10.bg-white.mb-4.p-4
                  span.fw-bold Otras metodologías
                  p
                  ul.lista-ul--color
                    li 
                      i.lista-ul__vineta
                      | PRINCE2.
                    li 
                      i.lista-ul__vineta
                      | PRiSM.
                    li 
                      i.lista-ul__vineta
                      | Materialización de beneficios.
                .col-10.mb-4.mb-md-0
                  img(src='@/assets/curso/tema3/linea-otras.png', alt='Otras metodologías')
          
              .row(titulo="PMBOK").justify-content-center
                .col-10.bg-white.mb-4.p-4
                  span.fw-bold El método PMBOK: 
                  | con cinco etapas que son: 
                  p
                  ul.lista-ul--color
                    li 
                      i.lista-ul__vineta
                      | Inicio.
                    li 
                      i.lista-ul__vineta
                      | Planificación.
                    li 
                      i.lista-ul__vineta
                      | Ejecución.
                    li 
                      i.lista-ul__vineta
                      | Seguimiento.
                    li 
                      i.lista-ul__vineta
                      | Cierre.
                .col-10.mb-4.mb-md-0
                  img(src='@/assets/curso/tema3/linea-pmbok.png', alt='El método PMBOK')

          .col.col-10.mb-4.mb-md-0
            p Cabe resaltar que, dependiendo de la envergadura del proyecto, estos tipos de metodologías pueden usarse de manera combinada o aleatoria, en función del rigor que requiera cada una de las fases. Por ejemplo, para la fase de identificación se puede utilizar la metodología del árbol de problemas, y definir la ejecución del proyecto con un enfoque de gestión Kanban. En todo caso, cuando se trata de proyectos a pequeña escala, los requisitos casi siempre vendrán dados por la convocatoria de ayudas a la financiación o los concursos a los que el aspirante se presente.
            p Para profundizar y conocer en detalle, en qué consisten estas metodologías, lo invitamos a ver en el material complementario 
              strong Metodologías de gestión de proyectos.

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    datosSlyder: [
      {
        titulo: 'Título del proyecto',
        texto:
          'Aporta en forma clara y precisa datos e información sobre el tema, el problema, o instituciones que participan en el proyecto; es un instrumento que unifica la temática y metodología del mismo, y sirve para diferenciarlo de otros, para caracterizar su temática y enunciar el contenido. Debe contener aspectos que permitan responder. ¿Qué actividad se realizará? ¿Dónde y cuándo? y ¿a quiénes va dirigido? Debe resumir el proyecto y especificar características. Al leerlo se debe comprender el proyecto.',
        imagen: require('@/assets/curso/tema3/slyder-fases-01.jpg'),
      },
      {
        titulo: 'Identificación de la organización y/o autores del proyecto',
        texto:
          'Incluye los datos relevantes de la organización o del autor(es) del proyecto, una breve descripción de la organización o resumen curricular del autor(es) del proyecto.',
        imagen: require('@/assets/curso/tema3/slyder-fases-02.jpg'),
      },
      {
        titulo: 'Identificación del proyecto/definición del problema',
        texto:
          'La naturaleza, carácter, categoría, tipo y finalidad, expresada a través de una descripción más o menos amplia, donde se expone la idea central para la que se pretende realizar con el proyecto.',
        imagen: require('@/assets/curso/tema3/slyder-fases-03.jpg'),
      },
      {
        titulo: 'Justificación del proyecto',
        texto:
          'Describe la importancia del problema, el porqué del proyecto y su viabilidad; argumenta de forma científica o técnica una problemática resultante de diagnóstico previo y considerado prioritario.',
        imagen: require('@/assets/curso/tema3/slyder-fases-04.jpg'),
      },
      {
        titulo: 'Objetivos',
        texto:
          'Constituyen el punto central de referencia de un proyecto, teniendo en cuenta que hablan sobre para qué se efectúa y que se espera al finalizar el proyecto.',
        imagen: require('@/assets/curso/tema3/slyder-fases-05.jpg'),
      },
      {
        titulo: 'Alcance',
        texto:
          'Se refiere a la delimitación de los alcances del proyecto, los cuales a su vez se relacionan con los recursos humanos, técnicos, físicos, de tiempo y financieros disponibles.',
        imagen: require('@/assets/curso/tema3/slyder-fases-06.jpg'),
      },
      {
        titulo: 'Cobertura geográfica o espacial',
        texto:
          'Se refiere al espacio o zona que cubrirá el proyecto en cuanto al área de influencia, lugar donde se realizará el proyecto.',
        imagen: require('@/assets/curso/tema3/slyder-fases-07.jpg'),
      },
      {
        titulo: 'Productos, resultados y efectos',
        texto:
          'Generalmente el producto es considerado como el resultado de un trabajo o de una actividad determinada; su realización debe comprobarse en tiempo y en consecución de los objetivos que estén y que sean realizados con los recursos disponibles.',
        imagen: require('@/assets/curso/tema3/slyder-fases-01.jpg'),
      },
      {
        titulo: 'Impacto del proyecto',
        texto:
          'Se refiere a los beneficios concretos que se espera conseguir con el proyecto después de haber alcanzado con éxito los objetivos. Se pretende demostrar cómo los logros del proyecto habrán modificado favorablemente y en forma estable las condiciones iniciales.',
        imagen: require('@/assets/curso/tema3/slyder-fases-08.jpg'),
      },
      {
        titulo: 'Beneficiarios',
        texto:
          'Dependen del carácter, naturaleza, categoría o tipo de proyecto; su composición es variada y diferente.  La distribución de la población se puede hacer desde el punto de vista social, económico, educativo, de tal manera que permite visualizar la población que puede constituirse en objeto de un proyecto.',
        imagen: require('@/assets/curso/tema3/slyder-fases-09.jpg'),
      },
      {
        titulo: 'Actividades',
        texto:
          'Son las acciones necesarias para alcanzar los resultados o productos del proyecto. Solo se incluyen las actividades que realiza el equipo de trabajo y que se establecen en relación con el tiempo en el que se ejecutarán',
        imagen: require('@/assets/curso/tema3/slyder-fases-10.jpg'),
      },
      {
        titulo: 'Recursos',
        texto:
          'Se refiere a los medios humanos y materiales disponibles que se invierten en las actividades y que son necesarios para la consecución de los objetivos.',
        imagen: require('@/assets/curso/tema3/slyder-fases-11.jpg'),
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
