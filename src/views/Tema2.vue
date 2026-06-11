<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 2
        h1 Gestión de resultados y evidencia de ejecución
      
      .row.justify-content-center.mb-5.bg-color-primario(data-aos="fade-right")
        .col-sm-12.col-lg-5.d-none.d-lg-block.mx-0.px-0
          img(src='@/assets/curso/temas/t2/1.png', alt='')
        .col-sm-12.col-lg-7.mx-0.px-0
          .p-4.text-white
            img.wcus-1.mb-5.d-none.d-lg-block(src='@/assets/curso/temas/t2/2.svg', alt='')
            p.mb-4 La ejecución de pruebas, sean estáticas o dinámicas, carece de valor si sus hallazgos no se gestionan de manera sistemática. La transición entre la fase operativa de evaluación y la fase analítica de mejora marca la diferencia entre un equipo que simplemente encuentra errores y uno que asegura la calidad integral del producto.
            p.mb-0 Este apartado se orienta a establecer planes de mejora basados en la evidencia empírica obtenida durante las pruebas. Para lograrlo, el aprendiz debe dominar procesos como el registro documental, el análisis de cobertura, la gestión de evidencias y la interpretación de resultados. La calidad de un software no se mide únicamente por la ausencia de fallas en su lanzamiento, sino por la rigurosidad con la que se documentaron, analizaron y resolvieron los problemas durante su construcción.
      
      
      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 De la ejecución de pruebas a la mejora
      
      .row.justify-content-center.mb-0(data-aos="fade-right")
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-2
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t2/3.svg')
            h3.text-center Ejecutar pruebas
            p.mb-0 Las pruebas permiten comparar el comportamiento esperado del sistema con el comportamiento real obtenido durante la evaluación.
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-2
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t2/4.svg')
            h3.text-center Registrar hallazgos
            p.mb-0 Cada resultado debe documentarse de manera objetiva, indicando si la prueba fue exitosa o fallida.
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-2
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t2/5.svg')
            h3.text-center Reunir evidencias
            p.mb-0 Las evidencias permiten demostrar lo ocurrido durante la ejecución y facilitan la reproducción de fallas.
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-2
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t2/6.svg')
            h3.text-center Analizar resultados
            p.mb-0 La información registrada sirve como base para medir cobertura, identificar riesgos y orientar decisiones de mejora.
      
      
      
      
      Separador
      #t_2_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
        h2 2.1 Registro de hallazgos, trazabilidad y evidencias
      
      p.mb-5 El primer eslabón en la cadena de la gestión de calidad es la captura objetiva de los resultados de cada caso de prueba ejecutado. Este proceso exige que el profesional en aseguramiento de calidad registre, de manera detallada, si el comportamiento observado en el sistema coincidió con el comportamiento esperado.
      
      .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5.mb-5.br-1(data-aos="fade-right")
        .bloque-texto-g__img.d-none.d-lg-block(
          :style="{'background-image': `url(${require_src('@/assets/curso/temas/t2/7.png')})`}"
        )
        .bloque-texto-g__texto.p-4.d-flex.flex-column.justify-content-center.br-2
          p.mb-3 Cuando ambas variables coinciden, el hallazgo se registra como exitoso, es decir, successful o pass. Cuando existe una desviación, por mínima que sea, se registra como fallido, es decir, fail. Esta categorización es fundamental para establecer el estado de salud del proyecto tecnológico en un momento determinado.
          p.mb-0 Desde una perspectiva pedagógica, el registro de hallazgos enseña el valor de la objetividad y la precisión. No basta con afirmar que un formulario “no funciona”; es necesario documentar en qué condiciones específicas se produjo la falla. El registro debe incluir la fecha y hora de la ejecución, el entorno de pruebas utilizado, por ejemplo, navegador, sistema operativo o versión del dispositivo móvil, los datos de entrada empleados y la salida real generada por el sistema.
      
      p.mb-5(data-aos="fade-right") Esta información constituye la materia prima sobre la cual los desarrolladores trabajarán posteriormente para aplicar las correcciones necesarias.
      
      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Elementos del registro de hallazgos
      
      AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bg-brown")(data-aos="fade-right")
        .row.justify-content-center(titulo="Estado de la prueba")
          .col-sm-12.col-lg-6
            p.mb-0 Indica si el caso de prueba fue exitoso, successful o pass, o si fue fallido, fail, según la comparación entre el resultado esperado y el resultado obtenido.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t2/8.png')
        .row.justify-content-center(titulo="Condiciones de ejecución")
          .col-sm-12.col-lg-6
            p.mb-0 Incluye datos como fecha, hora, navegador, sistema operativo, versión del dispositivo o entorno en el que se realizó la prueba.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t2/9.png')
        .row.justify-content-center(titulo="Datos de entrada")
          .col-sm-12.col-lg-6
            p.mb-0 Registra los valores específicos utilizados durante la prueba, ya que estos ayudan a reproducir el comportamiento del sistema.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t2/10.png')
        .row.justify-content-center(titulo="Salida real del sistema")
          .col-sm-12.col-lg-6
            p.mb-0 Describe la respuesta obtenida durante la ejecución, especialmente cuando existe una diferencia frente al resultado esperado.
          .col-sm-12.col-lg-6.d-none.d-lg-block
            img(src='@/assets/curso/temas/t2/11.png')


      .row.justify-content-center.mb-5.align-items-end(data-aos="fade-right")
        .col-sm-12.col-lg-3.d-none.d-lg-block
          img(src='@/assets/curso/temas/t2/12.png', alt='')
        .col-sm-12.col-lg-9
          img.wcus-1.mb-3.d-none.d-lg-block(src='@/assets/curso/temas/t2/13.svg', alt='')
          .bg-color-1.p-4
            p.mb-3 La trazabilidad es el principio que permite vincular cada prueba ejecutada con un requerimiento de negocio o funcional específico. Para garantizar esta conexión, en la industria tecnológica se emplea la Matriz de Trazabilidad de Requerimientos, conocida como RTM, por sus siglas en inglés. La comprensión de este instrumento es vital, ya que permite visualizar cómo una necesidad del cliente se transforma en una característica del software y, a su vez, cómo esa característica es validada por uno o varios casos de prueba.
            p.mb-0 En la práctica formativa, la trazabilidad evita que el equipo de desarrollo escriba pruebas innecesarias o que olvide evaluar funcionalidades críticas. Por ejemplo, en el desarrollo de un portal de educación virtual, un requerimiento puede estipular que “el sistema debe permitir la carga de archivos en formato PDF de hasta 5 MB”. La matriz de trazabilidad conectará este requerimiento con un caso de prueba de caja negra diseñado para validar precisamente esa restricción. Si el caso de prueba falla, la trazabilidad permite identificar inmediatamente qué requerimiento del cliente se encuentra en riesgo de incumplimiento.


      p.mb-5(data-aos="fade-right") Un hallazgo registrado sin evidencia carece de validez técnica. La estructuración de la evidencia implica recolectar artefactos digitales que demuestren de forma irrefutable el resultado de la prueba. Para los casos exitosos, la evidencia asegura que la funcionalidad fue validada correctamente antes de la entrega; para los casos fallidos, la evidencia es crucial para que el desarrollador pueda reproducir y comprender el error.

      .cajon.color-acento-contenido.p-4.mb-5(data-aos="fade-right")
        p.mb-0 Las formas más comunes de estructurar esta evidencia incluyen capturas de pantalla con anotaciones, grabaciones de video de la interacción con la interfaz, archivos de registro o logs generados por el servidor, y exportaciones del estado de la base de datos antes y después de la transacción. Pedagógicamente, la evidencia debe entenderse como un instrumento de comunicación técnica, no como una herramienta para penalizar al programador. Una evidencia bien estructurada elimina la ambigüedad, reduce los tiempos de depuración y fomenta un ambiente de trabajo colaborativo fundamentado en datos objetivos.
      
      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2  Ruta para documentar hallazgos con evidencia

      .bg-full-width.bg-fondo-1(data-aos="fade-right")
        .p-full-width 
          .row.justify-content-center.mb-0
            .col-sm-12.col-lg-8
                LineaTiempoE.color-acento-contenido
                  .row(titulo="Paso 1")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t2/14.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Registrar el resultado
                      p.mb-0 Se indica si el caso de prueba fue exitoso o fallido, comparando el comportamiento esperado con el comportamiento real.
                  .row(titulo="Paso 2")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t2/15.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Relacionar el requerimiento
                      p.mb-0 Se vincula el caso de prueba con el requerimiento correspondiente mediante una matriz de trazabilidad o RTM.
                  .row(titulo="Paso 3")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t2/16.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Recolectar evidencias
                      p.mb-0 Se guardan capturas, grabaciones, logs o exportaciones que permitan demostrar lo ocurrido durante la ejecución.
                  .row(titulo="Paso 4")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t2/17.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Facilitar la corrección
                      p.mb-0 La evidencia se organiza para que el equipo de desarrollo pueda reproducir, analizar y corregir la falla con mayor precisión.







      
      Separador
      #t_2_2.titulo-segundo.color-acento-contenido(data-aos='fade-right')
        h2 2.2 Cobertura de pruebas, métricas e impacto
      
      .row.justify-content-center.mb-5(data-aos="fade-right")
        .col-sm-12.col-lg-5.d-none.d-lg-block
          img(src='@/assets/curso/temas/t2/18.png', alt='')
        .col-sm-12.col-lg-7
          .row.justify-content-center.mb-4
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src='@/assets/curso/temas/t2/19.svg', alt='')
            .col-sm-12.col-lg-10 Determinar cuándo se ha probado lo suficiente es uno de los dilemas más recurrentes en el desarrollo de software. Es matemáticamente imposible ejecutar un número infinito de pruebas para cubrir todas las combinaciones posibles de datos e interacciones en un sistema complejo. Frente a esta limitación, surge el concepto de cobertura de pruebas, el cual permite cuantificar el alcance y la profundidad del esfuerzo de evaluación realizado.
          p.mb-0 Cuantificar la cobertura es esencial para tomar decisiones informadas sobre la liberación de un producto al mercado o su paso a la siguiente fase de desarrollo.
      p.mb-5(data-aos="fade-right") Las métricas de cobertura proporcionan un indicador numérico que refleja el progreso de la fase de aseguramiento de calidad. Existen diferentes niveles para medir esta cobertura. Por un lado, la cobertura de requerimientos calcula el porcentaje de funcionalidades solicitadas por el cliente que ya cuentan con casos de prueba diseñados y ejecutados. Por otro lado, la cobertura de código, más ligada a las pruebas de caja blanca y unitarias, calcula el porcentaje de líneas de código fuente que han sido ejecutadas por las pruebas automáticas.    


      .cajon.color-primario.p-4.mb-5(data-aos="fade-right")
        p.mb-0 Para ilustrar este cálculo de manera sencilla en un contexto formativo, la fórmula básica establece que la cobertura es igual al número de elementos evaluados dividido por el número total de elementos, multiplicado por cien. Si un aplicativo de gestión documental tiene 50 requerimientos funcionales aprobados y el aprendiz ha ejecutado pruebas exitosas para 40 de ellos, la cobertura funcional actual es del 80 %. Comprender estas métricas permite evaluar el riesgo residual del proyecto, asimilando que un nivel bajo de cobertura implica una alta probabilidad de que existan defectos ocultos en las áreas no evaluadas.

      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Fórmula básica de cobertura

      .cajon.color-acento-contenido.p-4.mb-5(data-aos="fade-right")
        .px-5
          p.mb-1.fw-bold Cobertura de pruebas = elementos evaluados / total de elementos × 100
          p.mb-0 Ejemplo: si existen 50 requerimientos funcionales y se han ejecutado pruebas exitosas para 40 de ellos, la cobertura funcional es del 80 %.


      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5.br-1(data-aos="fade-right")
        .bloque-texto-g__img.d-none.d-lg-block(
          :style="{'background-image': `url(${require_src('@/assets/curso/temas/t1/20.png')})`}"
        )
        .bloque-texto-g__texto.p-4.d-flex.flex-column.justify-content-center.br-2
          p.mb-3 El análisis de impacto es el proceso analítico que sigue a la cuantificación matemática de la cobertura. No todas las funcionalidades de un software poseen el mismo nivel de criticidad. Por tanto, una cobertura del 90 % podría parecer excelente, pero si el 10 % restante corresponde al módulo de pagos electrónicos de una tienda virtual, el riesgo para el negocio es inaceptablemente alto.
          p.mb-0 Con este análisis, la cobertura deja de interpretarse solo como un porcentaje y empieza a leerse en relación con la importancia estratégica de cada componente. Por esta razón, no basta con afirmar que se ha cubierto una alta proporción del sistema; también es necesario identificar qué funcionalidades quedaron sin evaluar, qué nivel de riesgo representan y qué consecuencias podrían generar para el usuario, el negocio o la operación del sistema.

      p.mb-3(data-aos="fade-right") El aprendiz debe aprender a ponderar las métricas de cobertura con base en la importancia estratégica de los componentes del sistema. Este análisis de completitud orienta los esfuerzos del equipo hacia las áreas de mayor riesgo. Si durante la cuantificación se identifica que un módulo crítico carece de casos de prueba, el líder de calidad debe ordenar el diseño y ejecución inmediata de evaluaciones para esa sección.

      p.mb-5(data-aos="fade-right") Así, la cuantificación deja de ser un simple reporte estadístico y se convierte en una herramienta dinámica de gestión de riesgos, permitiendo al profesional en formación tomar decisiones estratégicas sobre dónde invertir el tiempo y los recursos de pruebas restantes.

      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Decisiones a partir de la cobertura

      .row.justify-content-center.mb-0(data-aos="fade-right")
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-2
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t2/21.svg')
            h3.text-center Medir cobertura
            p.mb-0 Se calcula qué proporción de requerimientos, funcionalidades o código ha sido evaluada mediante casos de prueba.
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-2
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t2/22.svg')
            h3.text-center Identificar vacíos
            p.mb-0 Se reconocen áreas del sistema que aún no han sido evaluadas o que presentan baja cobertura.
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-2
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t2/23.svg')
            h3.text-center Analizar criticidad
            p.mb-0 Se determina si los componentes no cubiertos son de bajo, medio o alto impacto para el negocio o el usuario.
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-2
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t2/24.svg')
            h3.text-center Priorizar nuevas pruebas
            p.mb-0 Se decide dónde invertir tiempo y recursos para reducir riesgos antes de liberar o avanzar el producto.

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
