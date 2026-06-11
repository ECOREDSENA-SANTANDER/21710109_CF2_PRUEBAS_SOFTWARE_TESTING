<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 4
        h1 Planes de mejora y optimización continua
      
      .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5.br-1(data-aos="fade-right")
        .bloque-texto-g__img.d-none.d-lg-block(
          :style="{'background-image': `url(${require_src('@/assets/curso/temas/t4/1.png')})`}"
        )
        .bloque-texto-g__texto.p-4.d-flex.flex-column.justify-content-center.br-2
          p.mb-3 La gestión de resultados no finaliza con el registro de hallazgos, incidentes o métricas. Para que el proceso de pruebas aporte valor real al desarrollo de #[i software], la información recopilada debe transformarse en acciones de mejora. Esta fase permite analizar lo ocurrido durante la ejecución, reconocer fallas recurrentes, socializar aprendizajes y formular estrategias que fortalezcan tanto el producto tecnológico como el proceso de trabajo del equipo.
          p.mb-0 Los planes de mejora permiten pasar de la identificación del problema a la definición de acciones concretas, asignables y medibles. De esta manera, el proceso de #[i testing] no se entiende como un obstáculo dentro del desarrollo, sino como una fuente de aprendizaje técnico y organizacional que impulsa la calidad, la eficiencia y la evolución continua del #[i software].
      
      
      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 De los resultados a la mejora continua
      
      .row.justify-content-start.mb-5(data-aos="fade-right")
        .col-sm-12.col-lg-11.position-relative
          .avatar
            figure
              img(src="@/assets/curso/temas/t4/2.svg", alt="alt").img250
          
          .crd.crd--avatarHorizontal.crd--first.crd--bg-first.py-4
            .row.align-items-center
              .col-auto
                figure
                  img(src="@/assets/curso/temas/t4/3.svg", alt="alt").img100
              .col
                h5 Analizar resultados
                p Los registros, métricas e incidentes permiten identificar qué ocurrió durante el proceso de pruebas.
          
          .crd.crd--avatarHorizontal.crd--bg-second.py-4
            .row.align-items-center
              .col-auto
                figure
                  img(src="@/assets/curso/temas/t4/4.svg", alt="alt").img100
              .col
                h5 Reconocer causas
                p El análisis permite diferenciar errores del código, fallas de comunicación, retrasos o problemas del proceso.
        
          .crd.crd--avatarHorizontal.crd--bg-first.py-4
            .row.align-items-center
              .col-auto
                figure
                  img(src="@/assets/curso/temas/t4/5.svg", alt="alt").img100
              .col
                h5 Socializar aprendizajes
                p Las lecciones aprendidas deben compartirse para fortalecer el conocimiento del equipo de desarrollo.
          
          .crd.crd--avatarHorizontal.crd--bg-second.crd--last.py-4
            .row.align-items-center
              .col-auto
                figure
                  img(src="@/assets/curso/temas/t4/6.svg", alt="alt").img100
              .col
                h5 Formular mejoras
                p Los hallazgos se convierten en acciones correctivas, preventivas y estrategias de optimización continua.
      

      
      
      
      
      
      
      
      Separador
      #t_4_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
        h2 4.1 Lecciones aprendidas, retrospectiva y socialización del conocimiento
      
      
      img.mb-5.d-none.d-lg-block(src='@/assets/curso/temas/t4/7.png', alt='')  
      p.mb-3(data-aos="fade-right") El ciclo de desarrollo y pruebas de #[i software] es, por naturaleza, iterativo y empírico. Una vez finalizada la documentación formal de los resultados, el equipo debe llevar a cabo un ejercicio de introspección para evaluar su propio desempeño. Este análisis, a menudo enmarcado en ceremonias ágiles como la retrospectiva, es crucial para cultivar una mentalidad de mejora continua.
      p.mb-5(data-aos="fade-right") Identificar qué funcionó bien y qué falló en el proceso de evaluación asegura que los errores metodológicos no se repitan en futuras iteraciones o proyectos. Por esta razón, las lecciones aprendidas no deben asumirse como un cierre administrativo, sino como una oportunidad para mejorar la forma en que el equipo diseña, ejecuta, documenta y analiza las pruebas.
      
      
      .row.justify-content-center.mb-5.align-items-end(data-aos="fade-right")
        .col-sm-12.col-lg-3.d-none.d-lg-block
          img(src='@/assets/curso/temas/t4/8.png', alt='')
        .col-sm-12.col-lg-9
          .bg-color-1.p-4
            img.wcus-1.mb-3.d-none.d-lg-block(src='@/assets/curso/temas/t4/9.svg', alt='')
            p.mb-3 El primer paso de la retrospectiva consiste en realizar un análisis de causa raíz sobre las fallas procedimentales. Es fundamental diferenciar esto de los errores del código; aquí se evalúan los errores del equipo humano. Por ejemplo, si se descubre un defecto crítico de caja negra un día antes del lanzamiento oficial, es necesario analizar si el diseño de los casos de prueba comenzó demasiado tarde o si el entorno de pruebas no estaba configurado a tiempo.
            p.mb-0 Mediante técnicas de análisis como los “5 Porqués” o el Diagrama de Ishikawa, el aprendiz aprende a profundizar más allá de los síntomas superficiales para encontrar el origen de los problemas organizacionales. Por ejemplo, si un equipo detecta reiteradamente que sus casos de prueba están desactualizados frente a la versión final del #[i software], la lección aprendida podría indicar una falla de comunicación entre los analistas de requerimientos y el equipo de aseguramiento de calidad.
      
      p.mb-5(data-aos="fade-right") Identificar estas oportunidades de mejora es un componente central de la madurez profesional y del cumplimiento del resultado de aprendizaje asociado a la formulación de planes de mejora.

      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Ruta para identificar lecciones aprendidas
      
      .bg-full-width.bg-fondo-1(data-aos="fade-right")
        .p-full-width 
          .row.justify-content-center.mb-0
            .col-sm-12.col-lg-8
                LineaTiempoE.color-acento-contenido
                  .row(titulo="Paso 1")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t4/10.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Revisar el proceso
                      p.mb-0 Se analiza cómo se diseñaron, ejecutaron y documentaron las pruebas durante el ciclo de trabajo.
                  .row(titulo="Paso 2")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t4/11.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Identificar fallas recurrentes
                      p.mb-0 Se reconocen problemas repetidos, como casos de prueba desactualizados, fallas de comunicación o configuración tardía del entorno.
                  .row(titulo="Paso 3")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t4/12.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Analizar la causa raíz
                      p.mb-0 Se aplican técnicas como los “5 Porqués” o el Diagrama de Ishikawa para comprender el origen del problema.
                  .row(titulo="Paso 4")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t4/13.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Definir aprendizajes
                      p.mb-0 Se documentan conclusiones que permitan evitar la repetición de errores metodológicos en futuras iteraciones o proyectos.
                  
      
      .cajon.color-primario.p-4.mb-5(data-aos="fade-right")
        p.mb-3 Las lecciones aprendidas carecen de impacto si se quedan archivadas en un documento estático. La socialización de este conocimiento es el mecanismo a través del cual la experiencia individual se transforma en inteligencia colectiva. En el ámbito formativo, se debe motivar al aprendiz a compartir sus hallazgos, no desde la crítica destructiva, sino mediante talleres, reuniones de cierre o la actualización de bases de conocimiento internas del proyecto.
        p.mb-0 La socialización puede incluir la creación de guías de buenas prácticas derivadas de los errores cometidos. Si, por ejemplo, el equipo de pruebas descubre que las inyecciones SQL son vulnerabilidades frecuentes en el proyecto actual, la socialización puede consistir en capacitar brevemente a los desarrolladores sobre cómo parametrizar correctamente las consultas a la base de datos en los próximos ciclos de codificación.
      
      
      p.mb-5(data-aos="fade-right") Este flujo bidireccional de información fortalece la cohesión del equipo y eleva el estándar general de la producción de #[i software].
      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Formas de socializar el conocimiento
      
      AcordionA.mb-0(tipo="a" clase-tarjeta="tarjeta bg-brown")(data-aos="fade-right")
        .row.justify-content-center(titulo="Talleres internos")
          .col-sm-12.col-lg-6
            p.mb-0 Permiten compartir hallazgos, explicar causas de errores y proponer buenas prácticas para próximos ciclos de trabajo.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t4/14.png')
        .row.justify-content-center(titulo="Reuniones de cierre")
          .col-sm-12.col-lg-6
            p.mb-0 Facilitan la conversación del equipo sobre qué funcionó, qué falló y qué debe ajustarse en futuras iteraciones.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t4/15.png')
        .row.justify-content-center(titulo="Bases de conocimiento")
          .col-sm-12.col-lg-6
            p.mb-0 Conservan aprendizajes, guías y recomendaciones para que otros integrantes del equipo puedan consultarlos posteriormente.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t4/16.png')
        .row.justify-content-center(titulo="Guías de buenas prácticas")
          .col-sm-12.col-lg-6
            p.mb-0 Recogen orientaciones derivadas de errores reales, como vulnerabilidades frecuentes o fallas repetidas en el proceso de desarrollo.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t4/17.png')
       


      Separador
      #t_4_2.titulo-segundo.color-acento-contenido(data-aos='fade-right')
        h2 4.2 Acciones correctivas, preventivas y estrategias de optimización
      
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5.br-1(data-aos="fade-right")
        .bloque-texto-g__img.d-none.d-lg-block(
          :style="{'background-image': `url(${require_src('@/assets/curso/temas/t4/18.png')})`}"
        )
        .bloque-texto-g__texto.p-4.d-flex.flex-column.justify-content-center.br-2
          p.mb-3 El punto central de la gestión de resultados es la formulación estructurada de planes de mejora. Todos los registros, métricas e incidentes recopilados previamente deben materializarse en acciones concretas, asignables y medibles que optimicen tanto el producto tecnológico como el proceso de construcción subyacente.
          p.mb-0 Un plan de mejora es la respuesta proactiva a las debilidades identificadas, asegurando que la calidad del #[i software] evolucione positivamente en el tiempo. En la ingeniería de calidad, las soluciones se dividen conceptualmente en dos grandes categorías: acciones correctivas y acciones preventivas.


      .row.justify-content-center.mb-5.align-items-end(data-aos="fade-right")
        .col-sm-12.col-lg-8
          .bg-color-1.py-4.px-5.mb-5
            p.mb-3 Las acciones correctivas son reactivas; están diseñadas para solucionar un problema existente que ya ha impactado la calidad del #[i software] o del proceso. Por ejemplo, si las métricas revelan que los tiempos de ejecución de las pruebas manuales de regresión están retrasando las entregas, una acción correctiva sería reasignar recursos temporales o priorizar solo las pruebas de los módulos críticos.
            p.mb-0 Por otro lado, las acciones preventivas son proactivas; buscan eliminar la causa de un problema potencial antes de que ocurra. Siguiendo el mismo ejemplo, la acción preventiva a mediano plazo sería implementar un plan de capacitación en herramientas de automatización de pruebas para el equipo, de modo que en el futuro los ciclos de regresión se ejecuten de forma programática y rápida.
          p.mb-0 La habilidad para formular ambas tipologías de acciones demuestra una comprensión madura de la gestión de calidad, equilibrando la resolución de crisis inmediatas con la planificación estratégica.
        .col-sm-12.col-lg-4.d-none.d-lg-block
          img(src='@/assets/curso/temas/t4/19.png', alt='')

      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Acciones correctivas y preventivas

      .row.justify-content-center.mb-5(data-aos="fade-right")
        .col-sm-12.col-lg-3.d-none.d-lg-block
          img(src='@/assets/curso/temas/t4/20.png', alt='')
        .col-sm-12.col-lg-9
          TabsA.color-acento-botones
            .tarjeta.bg-color-3.p-4(titulo="Acciones correctivas")
              p.mb-0 Son acciones reactivas orientadas a solucionar un problema existente que ya afectó la calidad del #[i software] o del proceso.
            .tarjeta.bg-color-3.p-4(titulo="Ejemplo correctivo")
              p.mb-0 Si las pruebas manuales de regresión retrasan las entregas, se pueden reasignar recursos temporales o priorizar módulos críticos.
            .tarjeta.bg-color-3.p-4(titulo="Acciones preventivas")
              p.mb-0 Son acciones proactivas orientadas a eliminar la causa de un problema potencial antes de que ocurra.
            .tarjeta.bg-color-3.p-4(titulo="Ejemplo preventivo")
              p.mb-0 Si se prevén retrasos futuros en pruebas de regresión, se puede capacitar al equipo en herramientas de automatización de pruebas.
            .tarjeta.bg-color-3.p-4(titulo="Gestión de calidad")
              p.mb-0 La combinación de acciones correctivas y preventivas permite atender problemas inmediatos y fortalecer la planificación estratégica.

      .row.justify-content-center.mb-5.align-items-end(data-aos="fade-right")
        .col-sm-12.col-lg-5.d-none.d-lg-block
          img(src='@/assets/curso/temas/t4/21.png', alt='')
        .col-sm-12.col-lg-7
          .row.justify-content-center.mb-4
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src='@/assets/curso/temas/t3/10.svg', alt='')
            .col-sm-12.col-lg-10 
              p.mb-0 La formulación de un plan de mejora no es un evento aislado, sino parte del ciclo iterativo de Planificar, Hacer, Verificar y Actuar, conocido como Ciclo de Deming o PDCA. Las estrategias de optimización continúan integradas en los planes de mejora deben ser medibles mediante indicadores de seguimiento.

          p.mb-3 Al establecer un plan, el profesional define claramente qué se va a hacer, quién es el responsable, qué recursos se requieren, en qué plazo debe completarse y cómo se medirá el éxito de la intervención.
          p.mb-0 En un contexto práctico de desarrollo web, si la retrospectiva identifica que la interfaz gráfica presenta múltiples defectos de responsividad en dispositivos móviles, detectados mediante pruebas de caja negra, el plan de mejora establecería la obligación de incorporar simuladores móviles en las primeras fases del desarrollo #[i front-end].

      .cajon.color-acento-contenido.p-4.mb-5(data-aos="fade-right")
        p.mb-0 El éxito de esta estrategia de optimización se mediría comprobando, en el siguiente ciclo de pruebas, si la densidad de defectos relacionados con la interfaz móvil disminuyó significativamente. Así, el aprendiz comprende que el proceso de #[i testing] no es un obstáculo, sino el motor principal que impulsa la excelencia y la evolución técnica en la industria del #[i software].
      
      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Ciclo de mejora continua aplicado a pruebas

      .bg-full-width.bg-fondo-1(data-aos="fade-right")
        .p-full-width 
          .row.justify-content-center.mb-0
            .col-sm-12.col-lg-8
                LineaTiempoE.color-acento-contenido
                  .row(titulo="Paso 1")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t4/22.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Planificar
                      p.mb-0 Se define la acción de mejora, el responsable, los recursos requeridos, el plazo y el indicador de seguimiento.
                  .row(titulo="Paso 2")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t4/23.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Hacer
                      p.mb-0 Se implementa la acción definida, como una capacitación, ajuste metodológico o incorporación de herramientas de apoyo.
                  .row(titulo="Paso 3")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t4/24.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Verificar
                      p.mb-0 Se revisa si la acción produjo el efecto esperado, mediante indicadores como reducción de defectos o mejora en tiempos de prueba.
                  .row(titulo="Paso 4")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t4/25.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Actuar
                      p.mb-0 Se institucionaliza la mejora cuando funciona o se ajusta la estrategia cuando los resultados no son suficientes.









  </template>

<script>
export default {
  name: 'Tema1',
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
