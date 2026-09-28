<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 7
      h1 Normatividad, seguridad y trazabilidad en el proceso de pruebas de <em>software</em>

    .row.align-items-center(data-aos="fade-down")
      .col-lg-5.d-none.d-lg-block
        figure
          img(src='@/assets/curso/tema7/1.png', alt='', style="width: 480px").m-auto
      .col-lg-7
        .row.justify-content-center.mt-4
          .col-lg-12
            .row.align-items-center
              .col-lg-12
                .cajon.color1.p-4
                  p.mb-0 El proceso de pruebas de software debe desarrollarse considerando normas, estándares y lineamientos vigentes que orienten la calidad, la seguridad y la adecuada gestión de la información. Su aplicación permite establecer criterios para planificar, ejecutar, documentar y controlar las pruebas, procurando que los procedimientos y herramientas utilizados respondan a los requisitos técnicos y organizacionales.

        p.mt-4 La gestión de la información constituye un aspecto fundamental durante las pruebas. Por ello, deben establecerse mecanismos de protección y copias de seguridad que permitan preservar los datos, evidencias, configuraciones y resultados generados durante el proceso. Estas medidas contribuyen a prevenir pérdidas de información, mantener su disponibilidad y facilitar su recuperación cuando sea necesario.

    .bloque-texto-g.bloque-texto-g--inverso.bg-3.p-3.p-sm-4.p-md-5.mt-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema7/2.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Asimismo, la trazabilidad permite establecer relaciones entre los requisitos, los casos de prueba, los resultados obtenidos y las incidencias identificadas, favoreciendo el seguimiento y la verificación del proceso. De esta manera, es posible disponer de evidencias que permitan comprobar qué se evaluó, mediante qué procedimiento, cuáles fueron los resultados y qué acciones se realizaron posteriormente.

    p.mt-4 Los conceptos, técnicas, procedimientos y herramientas de prueba se articulan con estos lineamientos para garantizar que la validación se realice de manera organizada, reproducible y documentada. Así, la aplicación conjunta de criterios normativos, mecanismos de respaldo y prácticas de trazabilidad fortalece la confiabilidad y el control del proceso de pruebas.
    
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
