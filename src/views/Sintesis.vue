<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p La implementación de pruebas y mejora del #[i software] permite comprender que la calidad de una solución tecnológica no se asegura únicamente al final del desarrollo, sino durante todo el proceso. En este componente formativo se abordaron las pruebas estáticas, de caja negra, de caja blanca y unitarias como técnicas que permiten prevenir errores, validar funcionalidades, revisar la lógica interna del código y fortalecer la confiabilidad del producto. De esta manera, el aprendiz reconoce que probar un sistema implica aplicar procedimientos técnicos, registrar resultados y tomar decisiones con base en evidencias.
    p Asimismo, la gestión de resultados permite transformar los hallazgos del proceso de pruebas en información útil para la mejora continua. El registro de hallazgos, la trazabilidad, la estructuración de evidencias, la cobertura de pruebas, el reporte de incidentes, los informes de resumen, las métricas de calidad y las lecciones aprendidas aportan a la formulación de acciones correctivas, preventivas y estrategias de optimización. Así, el proceso de #[i testing] se convierte en una práctica técnica y analítica que contribuye a entregar soluciones de #[i software] más confiables, seguras, usables y alineadas con las necesidades del usuario y del proyecto.

    .row.justify-content-center
      .col-lg-10.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/sintesis.svg", alt="Mapa conceptual titulado Implementación de pruebas y mejora del software. El esquema presenta cómo la implementación de pruebas permite asegurar la calidad del producto digital. Se organiza en tres bloques principales: implementación de pruebas, gestión de resultados e incidentes y documentación. En la implementación de pruebas se incluyen pruebas estáticas, de caja negra, de caja blanca y unitarias. En la gestión de resultados se relacionan hallazgos, estados pass y fail, evidencias, trazabilidad, cobertura e impacto. En incidentes y documentación se integran bug, ticket, ciclo del defecto, informe resumen y métricas de calidad. Estos elementos se conectan con la mejora continua, que incluye lecciones aprendidas, retrospectiva, causa raíz, acciones correctivas, preventivas y PDCA. El mapa concluye con el resultado final esperado: software confiable, seguro, usable y alineado con las necesidades del usuario y del proyecto.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
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
