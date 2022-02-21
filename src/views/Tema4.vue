<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Presentar proyectos a convocatorias y concursos

    .row.justify-content-center
      .col.col-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema4/img01.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 A raíz de la implementación de la Ley Naranja 1834 de 2017, el país ha abierto espacios significativos para el desarrollo de las industrias culturales y creativas
              br
              br
              | Entre esos espacios se encuentra la creación de convocatorias para el desarrollo y fortalecimiento de proyectos artísticos y culturales, que se suman a las que ya venían de años anteriores como la Ley Filmación Colombia (2012) y el programa de Estímulos del Ministerio de Cultura.
        br
        p Los requerimientos para presentarse en una convocatoria en Colombia son diferentes, dependiendo de las condiciones que establezca la propia convocatoria, pero en general tienen que ver con tener un documento del proyecto o propuesta, ser ciudadano colombiano mayor de edad, no tener impedimentos para concursar con el Estado, no haber sido ganador en convocatorias anteriores y cumplir con los requisitos documentales que se soliciten.      
        br
        .row.mb-5.bgLineaTiempo
          .col.col-12.col-md-8.p-4
            p Muchas convocatorias están restringidas a personas jurídicas o grupos constituidos, pero otras dan libre acceso también a personas naturales.
            p En el caso de los concursos, se debe contar con la pieza o contenido con el que se quiere participar tal y como lo establezca la dirección del evento y en la mayoría de los casos, contar con registro de propiedad intelectual.
          .col.col-12.col-md-4
            picture
              img(src='@/assets/curso/tema4/img02.svg', alt='Convocatorias', class='img-fluid')

        p Para Pedro Fuentes Rueda (2020), en el artículo Claves fundamentales para hacer un buen pitching audiovisual, en el caso de los proyectos audiovisuales, en los últimos tiempos se ha impuesto el PITCHING como metodología para presentar los proyectos ante posibles financiadores. PITCHING quiere decir lanzar y, en proyectos audiovisuales se refiere a la venta de series, de largometrajes, de documentales, o de programas de televisión.

        .row.justify-content-center
          .col.col-10
            .bloque-texto-c.contenedor1.p-4.mb-4
              i.fas.fa-quote-right
              h2.mb-2 Un pitching puede darse en una reunión individual, pero el formato más habitual consiste en una presentación pública ante posibles inversores, productores y cadenas, en una presentación que dura alrededor de diez minutos y que se puede apoyar en un Power Point. Tras esto, llega un turno de preguntas por parte del público asistente.
              span - Pedro Fuentes Rueda, 2020

            p Para profundizar sobre el Pitching audiovisual, se invita a ver el video Pitching, cómo vender nuestro proyecto, el cual se encuentra en el material complementario

          .col.col-5.mt-4
            img(src='@/assets/curso/tema4/img03.jpg', alt='Convocatorias para proyectos', class='img-fluid')
          
          .col.col-10.mt-4
            hr.tema4
            br
            p Anualmente, a través de diversos organismos y entidades, el estado colombiano otorga recursos financieros para apoyar la generación o el mantenimiento de iniciativas. Las fechas para estas ayudas se distribuyen a lo largo del año y habitualmente tienen un tiempo suficiente entre su apertura y cierre. En todo caso, lo recomendable es contar con una idea clara y sólida, o un avance del producto final, para no fallar en la fecha de convocatoria, ya que en ocasiones puede ser lento completar los requisitos documentales que se solicitan.
            
            img.mb-4(src='@/assets/curso/tema4/img04.jpg', alt='Convocatorias para proyectos', class='img-fluid')

          .row.mt-5
            .col.col-12.col-md-6
              table.tabla1-tema4
                thead
                  tr
                    th Convocatorias para proyectos artísticos y culturales y festivales
                tbody
                  tr
                    td 
                      p Algunas de las convocatorias de carácter general (no específicas para proyectos audiovisuales) son las siguientes:
                      ul
                        li - Programa Nacional de Estímulos
                        li - Programa departamental de Estímulos
                        li - Programa Distrital de Estímulos 2021
                        li - INNpulsa
                        li - Convocatoria Jóvenes en Movimiento
                        li - Convocatoria Laboratorio Startup de APPS.CO 
                        li - Semilleros de Emprendimiento Digital de Apps.co
                        li - Fondo Emprender del Sena
                        li - Programa Nacional de Concertación Cultural
                        li - Festivales de emprendimiento: Héroes Fest e InspiraTIC
              a.anexo.mb-4(href="https://economianaranja.gov.co/convocatorias/" target="_blank")
                .anexo__texto
                  p Para conocer en detalle las convocatorias y otras ayudas para la financiación de proyectos se puede visitar la página web
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
              
              a.anexo.mb-4(:href="obtenerLink('/downloads/OKEst_Formato de propuesta creativa.pdf')" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-pdf.svg")
                .anexo__texto
                  p Finalmente puede verificar el formato de Propuesta Creativa para la convocatoria audiovisual del Mintic 2021 a través del siguiente recurso

            .col.col-12.col-md-6
              table.tabla2-tema4
                thead
                  tr
                    th Convocatorias para proyectos audiovisuales
                tbody
                  tr
                    td 
                      p Algunas de las convocatorias específicas para proyectos audiovisuales son las siguientes:
                      ul
                        li - Convocatorias Audiovisuales Mintic
                        li - Crea digital
                        li - Ampliación beneficios Ley Filmación Colombia al sector audiovisual
                        li - Ley 814 de 2003: Estímulos e incentivos para las creación, producción, coproducción y realización de largometrajes y cortometrajes colombianos
                        li - Festival de Cine Verde de Barichara
                        li - Festival Internacional de Cine Independiente de Villa de Leyva
                        li - Festival Internacional de Cine de Cartagena
                        li - Festival de Cine Corto de Popayán
                        li - Festival de Cine de Bogotá 
                        li - Festival Internacional de Cine de Cali
                        li - Festival Internacional de Cine de Santander
                        li - Festival Internacional de Cine de Barranquilla
                        li - Festival de Cine e Infancia y Adolescencia
              br
              a.anexo.mb-4(href="https://mincultura.gov.co/areas/cinematografia/Paginas/Festivales.aspx" target="_blank")
                .anexo__texto
                  p Para conocer en detalle el total de festivales y muestras de cine colombiano que se realizan en el país, se puede visitar el siguiente enlace:
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")




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
