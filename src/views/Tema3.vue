<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 3
        h1 Gestión de incidentes y documentación de pruebas
      
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5.br-1(data-aos="fade-right")
        .bloque-texto-g__img.d-none.d-lg-block(
          :style="{'background-image': `url(${require_src('@/assets/curso/temas/t3/1.png')})`}"
        )
        .bloque-texto-g__texto.p-4.d-flex.flex-column.justify-content-center.br-2
          p.mb-3 La gestión de incidentes y la documentación de pruebas permiten transformar los resultados de la ejecución en información útil para el equipo de desarrollo, los líderes del proyecto y las partes interesadas. Cuando una prueba falla, no basta con indicar que existe un error; es necesario registrar el incidente con precisión, explicar cómo reproducirlo, documentar la evidencia y consolidar los resultados para facilitar la toma de decisiones sobre la calidad del #[i software].
          p.mb-0 Este proceso fortalece la comunicación técnica entre quienes evalúan el sistema y quienes realizan las correcciones. Además, permite identificar patrones de fallas, analizar la eficiencia del proceso de pruebas y presentar una visión clara del estado real del producto tecnológico.
      
      
      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 De la falla al informe de calidad
      


      .row.justify-content-center.mb-0(data-aos="fade-right")
        .col-md-6.col-xl.mb-4.mb-xl-0
          .tarjeta-numerada.color-primario.p-5.hcus-3
            .tarjeta-numerada__numero
              .h2 1
            p.text-center 
              b Prueba fallida
            p.text-center La prueba evidencia una diferencia entre el resultado esperado y el resultado obtenido.

        .col-md-6.col-xl.mb-4.mb-xl-0
          .tarjeta-numerada.color-secundario.p-5.hcus-3
            .tarjeta-numerada__numero
              .h2 2
            p.text-center 
              b Reporte de incidente
            p.text-center El hallazgo se documenta con precisión técnica para facilitar su análisis y corrección.

        .col-md-6.col-xl.mb-4.mb-xl-0
          .tarjeta-numerada.color-acento-contenido.p-5.hcus-3
            .tarjeta-numerada__numero
              .h2 3
            p.text-center 
              b Gestión del defecto
            p.text-center  El incidente pasa por estados de revisión, asignación, corrección, confirmación y cierre.

        .col-md-6.col-xl.mb-4.mb-xl-0
          .tarjeta-numerada.color-adicional-1.p-5.hcus-3
            .tarjeta-numerada__numero
              .h2 4
            p.text-center 
              b Documentación integral
            p.text-center   Los casos, métricas e incidentes se consolidan en informes que apoyan la toma de decisiones.


      

      Separador
      #t_3_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
        h2 3.1 Reporte de incidentes, estructura y ciclo de vida del defecto
      
      
      .row.justify-content-center.mb-5.align-items-end(data-aos="fade-right")
        .col-sm-12.col-lg-7
          p.mb-4 Cuando una prueba se registra como fallida, el proceso natural es la creación de un reporte de incidente, comúnmente conocido en el ámbito informático como #[i bug]. Reportar un incidente no consiste simplemente en notificar que algo se ha roto; es un proceso formal de documentación que exige precisión técnica y claridad descriptiva.
          .cajon.color-primario.px-5.py-4.mb-0
            p.mb-0 La calidad del reporte de un defecto impacta directamente en la velocidad con la que el equipo de desarrollo podrá solucionarlo. Por esta razón, esta competencia se convierte en un pilar importante dentro del aseguramiento de la calidad, ya que permite comunicar el problema de forma comprensible, reproducible y útil para su corrección.
        .col-sm-12.col-lg-5.d-none.d-lg-block
          img(src='@/assets/curso/temas/t3/2.png', alt='')
      
      p.mb-5(data-aos="fade-right") Antes de continuar con el ciclo de vida del defecto, se presenta el pódcast “Cuando una prueba falla: reportar, corregir y aprender”. Este recurso permite comprender, mediante una conversación aplicada, por qué una prueba fallida debe convertirse en información técnica clara, completa y reproducible. A través de un ejemplo relacionado con la carga de archivos PDF en una plataforma académica, se explica la importancia de documentar el incidente, registrar evidencias, diferenciar el resultado esperado del resultado real y facilitar la comunicación entre el evaluador, el desarrollador y el líder técnico.
      
      
      img.mb-0.d-none.d-lg-block(src='@/assets/curso/temas/t3/3.png')(data-aos='fade-right')
      .row.justify-content-center.g-0.bg-color-primario.mb-5(data-aos='fade-right')
        .col-12
          .tarjeta.clr--pink.p-4.rounded-0.h-100
            .tarjeta.bg-white.p-4
              TarjetaAudio.color-acento-botones.mb-0.p-4(
              texto="Pódcast. Cuando una prueba falla: reportar, corregir y aprender"
              :audio="podcast"
          )

      .bloque-texto-g.bloque-texto-g--inverso.color-acento-botones.p-3.p-sm-4.p-md-5.mb-5.br-1(data-aos="fade-right")
        .bloque-texto-g__img.d-none.d-lg-block(
          :style="{'background-image': `url(${require_src('@/assets/curso/temas/t3/4.png')})`}"
        )
        .bloque-texto-g__texto.p-4.d-flex.flex-column.justify-content-center.br-2
          p.mb-3 El concepto central en la gestión de incidentes es el ciclo de vida del defecto, el cual describe los diferentes estados por los que atraviesa un error desde el momento en que es descubierto hasta que es solucionado y cerrado definitivamente. En un entorno profesional o formativo simulado, este flujo de trabajo organiza la comunicación entre el evaluador, también llamado #[i tester], y el programador o desarrollador.
          p.mb-0 Un ciclo de vida estándar inicia cuando el incidente es reportado con el estado “Nuevo”. Posteriormente, un líder técnico lo revisa y, si es válido, lo pasa al estado “Asignado”, derivándolo al desarrollador responsable. Mientras el programador trabaja en la solución, el estado cambia a “En progreso”. Una vez corregido el código, el defecto se marca como “Resuelto” o “Listo para prueba”.

      .cajon.color-acento-contenido.p-4.mb-5(data-aos="fade-right")
        p.mb-0 En este punto, la responsabilidad retorna al evaluador, quien debe ejecutar nuevamente la prueba original, conocida como prueba de confirmación. Si el error desapareció, el defecto se marca como “Cerrado”; si persiste, se marca como “Reabierto”, reiniciando el ciclo. Este flujo permite comprender que la detección de un error es solo el inicio de un proceso colaborativo de saneamiento del código.

      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Ciclo de vida del defecto

      .bg-full-width.bg-fondo-1(data-aos="fade-right")
        .p-full-width 
          .row.justify-content-center.mb-0
            .col-sm-12.col-lg-8
                LineaTiempoE.color-acento-contenido
                  .row(titulo="Momento 1")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t3/5.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Nuevo
                      p.mb-0 El incidente se reporta por primera vez después de identificar una diferencia entre el resultado esperado y el resultado obtenido.
                  .row(titulo="Momento 2")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t3/6.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Asignado
                      p.mb-0 Un líder técnico revisa el incidente y lo deriva al desarrollador responsable cuando el reporte es válido.
                  .row(titulo="Momento 3")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t3/7.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 En progreso
                      p.mb-0 El desarrollador analiza la causa del defecto y trabaja en la corrección correspondiente.
                  .row(titulo="Momento 4")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t3/8.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Resuelto o listo para prueba
                      p.mb-0 El código ha sido corregido y el defecto queda disponible para una nueva validación.
                  .row(titulo="Momento 4")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t3/9.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Cerrado o reabierto
                      p.mb-0 Si la prueba de confirmación demuestra que el error fue solucionado, el defecto se cierra. Si el error persiste, se reabre y el ciclo continúa.


       
      .row.justify-content-center.mb-5.align-items-end(data-aos="fade-right")
        .col-sm-12.col-lg-5.d-none.d-lg-block
          img(src='@/assets/curso/temas/t3/11.png', alt='')
        .col-sm-12.col-lg-7
          .row.justify-content-center.mb-0
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src='@/assets/curso/temas/t3/10.svg', alt='')
            .col-sm-12.col-lg-10 Para que el ciclo de vida fluya sin fricciones, el documento o ticket que describe el incidente debe estar estructurado meticulosamente. Un reporte ineficiente, que incluya frases vagas como “la pantalla se queda en blanco”, genera frustración y pérdida de tiempo. Por el contrario, un reporte bien elaborado actúa como un manual de instrucciones para reproducir la falla.
          p.mb-0 Todo incidente debe contener un título descriptivo y conciso, la severidad del error, la prioridad, el entorno de ejecución donde ocurrió la falla y, especialmente, los pasos para reproducir el problema. Además, se debe contrastar de manera explícita el resultado esperado frente al resultado actual, adjuntando la evidencia estructurada previamente. Al dominar esta estructura, se facilita la resolución ágil de problemas y se demuestra profesionalismo en la comunicación técnica.

      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Estructura de un reporte de error efectivo


      AcordionA.mb-0(tipo="a" clase-tarjeta="tarjeta bg-brown")(data-aos="fade-right")
        .row.justify-content-center(titulo="Título descriptivo")
          .col-sm-12.col-lg-6
            p.mb-0 Resume el defecto de manera clara y concisa para que el equipo identifique rápidamente el problema reportado.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t3/12.png')
        .row.justify-content-center(titulo="Severidad")
          .col-sm-12.col-lg-6
            p.mb-0 Indica el impacto del error en el sistema, desde un defecto crítico hasta uno cosmético.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t3/13.png')
        .row.justify-content-center(titulo="Prioridad")
          .col-sm-12.col-lg-6
            p.mb-0 Define la urgencia con la que el defecto debe ser atendido por el equipo responsable.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t3/14.png')
        .row.justify-content-center(titulo="Entorno de ejecución")
          .col-sm-12.col-lg-6
            p.mb-0 Describe las condiciones en las que ocurrió la falla, como navegador, sistema operativo, versión o dispositivo utilizado.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t3/15.png')
        .row.justify-content-center(titulo="Pasos para reproducir")
          .col-sm-12.col-lg-6
            p.mb-0 Presenta la secuencia exacta de acciones realizadas por el evaluador para que el equipo pueda repetir la falla.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t3/16.png')
        .row.justify-content-center(titulo="Resultado esperado y resultado actual")
          .col-sm-12.col-lg-6
            p.mb-0 Compara lo que el sistema debía hacer con lo que realmente ocurrió durante la ejecución.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t3/17.png')
        .row.justify-content-center(titulo="Evidencia asociada")
          .col-sm-12.col-lg-6
            p.mb-0 Incluye capturas, grabaciones, archivos de registro o documentos que permitan comprender y validar el incidente.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t3/18.png')
















      Separador
      #t_3_2.titulo-segundo.color-acento-contenido(data-aos='fade-right')
        h2 3.2 Informes de resumen y métricas de calidad
      
      img.mb-5.d-none.d-lg-block(src='@/assets/curso/temas/t3/19.png', alt='')  
      p.mb-3(data-aos="fade-right") A medida que finaliza un ciclo o nivel de pruebas, toda la información fragmentada, como casos exitosos, casos fallidos, métricas de cobertura y reportes de incidentes, debe ser consolidada para ofrecer una visión panorámica de la calidad del producto. La documentación integral es el mecanismo a través del cual el equipo de calidad comunica el estado real del #[i software] a las partes interesadas, conocidas como #[i stakeholders], tales como gerentes de proyecto, clientes o, en el contexto formativo, instructores.
      p.mb-5(data-aos="fade-right") El informe de resumen de pruebas es un documento formal que compila los resultados de todo el esfuerzo de aseguramiento de calidad. Este artefacto no debe ser una lista interminable de datos técnicos, sino un resumen ejecutivo diseñado para facilitar la toma de decisiones.


      .cajon.color-primario.p-4.mb-5(data-aos="fade-right")
        p.mb-3 En este informe se debe sintetizar qué componentes del sistema fueron evaluados, qué técnicas se aplicaron, qué entorno se configuró y cuáles fueron los principales obstáculos encontrados. La redacción de este informe fomenta la capacidad de síntesis y la comunicación gerencial.
        p.mb-0 Por ejemplo, en lugar de detallar cada uno de los 200 incidentes encontrados en un sistema de reservas en línea, el informe puede agrupar la información destacando que el 60 % de las fallas se concentraron en la pasarela de pagos, lo cual señala un problema sistémico en la integración con el banco. Esta consolidación permite a los líderes del proyecto entender dónde están los cuellos de botella de calidad sin perderse en el microdetalle de los casos individuales.

      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Contenido de un informe de resumen de pruebas


      .row.justify-content-center.mb-5(data-aos="fade-right")
        .col-sm-12.col-lg-3.d-none.d-lg-block
          img(src='@/assets/curso/temas/t3/20.png', alt='')
        .col-sm-12.col-lg-9
          TabsA.color-acento-botones
            .tarjeta.bg-color-3.p-4(titulo="Componentes evaluados")
              p.mb-0 Identifica los módulos, funcionalidades o documentos que hicieron parte del ciclo de pruebas.
            .tarjeta.bg-color-3.p-4(titulo="Técnicas aplicadas")
              p.mb-0 Resume los tipos de pruebas utilizados, como pruebas funcionales, no funcionales, estáticas, dinámicas, de caja negra o de caja blanca.
            .tarjeta.bg-color-3.p-4(titulo="Entorno configurado")
              p.mb-0 Describe las condiciones técnicas utilizadas durante la ejecución, como ambiente, navegador, sistema operativo, versión o dispositivos.
            .tarjeta.bg-color-3.p-4(titulo="Obstáculos encontrados")
              p.mb-0 Presenta las principales dificultades del proceso, tales como fallas recurrentes, bloqueos, limitaciones de entorno o problemas de integración.
            .tarjeta.bg-color-3.p-4(titulo="Resultados relevantes")
              p.mb-0 Sintetiza los hallazgos más importantes para apoyar decisiones sobre corrección, liberación o continuidad del proyecto.


      .row.justify-content-center.mb-5.align-items-end(data-aos="fade-right")
        .col-sm-12.col-lg-8
          .bg-color-1.py-4.px-5.mb-4
            p.mb-3 Junto con el resumen narrativo, la documentación integral debe incluir una sección cuantitativa robusta. La consolidación de métricas de calidad agrupa indicadores clave de rendimiento, conocidos como KPIs, relacionados con el proceso de pruebas.

            p.mb-0 Algunas de las métricas más relevantes incluyen la densidad de defectos, entendida como el número de errores encontrados por cada mil líneas de código o por módulo funcional; el tiempo promedio de resolución de incidentes; y la tasa de defectos rechazados, es decir, reportes creados por el #[i tester] que resultaron no ser errores reales.
          p.mb-3 El análisis de estas métricas permite evaluar no solo la calidad del #[i software], sino también la eficiencia del propio proceso de pruebas. Si la tasa de defectos rechazados es muy alta, puede sugerir que el equipo de pruebas no comprende adecuadamente los requerimientos funcionales. Si el tiempo de resolución es excesivamente largo, puede indicar falta de recursos o de pericia técnica en el equipo de desarrollo.
          p.mb-0 Aprender a interpretar estos datos dota al aprendiz de herramientas para liderar procesos de calidad basados en evidencia empírica. 
        .col-sm-12.col-lg-4.d-none.d-lg-block
          img(src='@/assets/curso/temas/t3/21.png', alt='')
  

      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Métricas para evaluar la calidad del proceso

      .row.justify-content-center.mb-0(data-aos="fade-right")
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-2
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t3/22.svg')
            h3.text-center Densidad de defectos 
            p.mb-0 Relaciona la cantidad de errores encontrados con el tamaño del código o con un módulo funcional específico.
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-2
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t3/23.svg')
            h3.text-center Tiempo promedio de resolución 
            p.mb-0 Permite estimar cuánto tarda el equipo en solucionar los incidentes reportados.
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-2
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t3/24.svg')
            h3.text-center Tasa de defectos rechazados 
            p.mb-0 Indica cuántos reportes creados por el tester no correspondían realmente a defectos del sistema.
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-2
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t3/25.svg')
            h3.text-center Interpretación de resultados 
            p.mb-0 Ayuda a identificar problemas de comprensión de requisitos, falta de recursos o necesidades de mejora en el proceso de pruebas.










  </template>

<script>
import podcast from '@/assets/actividad/audio/success.mp3'
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
    podcast: podcast,
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
