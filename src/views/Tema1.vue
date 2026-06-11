<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 1
        h1 Implementación de pruebas manuales y unitarias de #[i software]
      
      
      .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5.mb-5.br-1(data-aos="fade-right")
        .bloque-texto-g__img.d-none.d-lg-block(
          :style="{'background-image': `url(${require_src('@/assets/curso/temas/t1/1.png')})`}"
        )
        .bloque-texto-g__texto.p-4.d-flex.flex-column.justify-content-center.br-2
          p.mb-3 El proceso de aseguramiento de la calidad inicia con la comprensión profunda de las diferentes técnicas de evaluación disponibles y su correcta aplicación según la fase del proyecto. La implementación de pruebas manuales y unitarias no responde a un ejercicio de improvisación, sino a un procedimiento técnico estandarizado que busca identificar discrepancias entre el comportamiento esperado de un sistema y su comportamiento real.
          p.mb-0 En este apartado se desarrollan enfoques estáticos y dinámicos que permiten a los equipos de desarrollo detectar anomalías desde las etapas más tempranas de conceptualización hasta la validación del código ya construido. Esta sección se encuentra directamente articulada con el resultado de aprendizaje orientado a la implementación de pruebas manuales y unitarias de acuerdo con estándares y procedimientos técnicos.
      
      
      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Implementación de pruebas en el desarrollo de #[i software]
      
      .row.justify-content-center.mb-0(data-aos="fade-right")
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-1
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t1/2.svg')
            h3.text-center Procedimiento técnico
            p.mb-0 La implementación de pruebas requiere criterios, pasos y técnicas definidas previamente para evitar la improvisación.
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-1
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t1/3.svg')
            h3.text-center Detección de discrepancias
            p.mb-0 Las pruebas permiten identificar diferencias entre el comportamiento esperado del sistema y su comportamiento real.
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-1
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t1/4.svg')
            h3.text-center Enfoques de evaluación
            p.mb-0 El proceso integra enfoques estáticos y dinámicos para revisar artefactos, código y funcionalidades.
        .col-sm-12.col-md-6.col-lg-3
          .tarjeta--boton.color-primario.p-4.mb-cus.hcus-1
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/temas/t1/5.svg')
            h3.text-center Relación con el aprendizaje
            p.mb-0 La implementación de pruebas manuales y unitarias fortalece competencias técnicas necesarias para el aseguramiento de la calidad del #[i software].
      
      Separador
      #t_1_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
        h2 1.1 Pruebas estáticas y prevención temprana 
      
      
      img.d-none.d-lg-block.mb-5(src='@/assets/curso/temas/t1/6.png', alt='')(data-aos="fade-right")
      p.mb-5(data-aos="fade-right") Las pruebas estáticas representan el primer filtro de calidad en cualquier proyecto de #[i software]. A diferencia de las pruebas dinámicas, que requieren la ejecución del código, las pruebas estáticas se enfocan en la revisión exhaustiva de los artefactos del proyecto antes de que el #[i software] sea compilado o ejecutado. Este enfoque preventivo se basa en la premisa de que corregir un error en la fase de requerimientos o diseño es significativamente más económico y requiere menos esfuerzo que solucionarlo cuando el sistema ya se encuentra en fase de producción.
      
      .row.justify-content-center.mb-5.align-items-end(data-aos="fade-right")
        .col-sm-12.col-lg-8
          .bg-color-1.p-4.mb-4
            p.mb-0 Comprender las pruebas estáticas implica reconocerlas como un ejercicio de lectura crítica y escrutinio analítico. En este caso, no se busca “romper” el sistema interactuando con él, sino examinar la documentación, los modelos de datos, las historias de usuario y el código fuente en busca de ambigüedades, inconsistencias, desviaciones de los estándares de codificación o lógica defectuosa. Existen diversas técnicas para llevar a cabo estas pruebas, entre las que destacan las revisiones informales, las inspecciones formales, las revisiones técnicas y el análisis estático de código mediante herramientas automatizadas que detectan vulnerabilidades de seguridad o malas prácticas de programación, conocidas como #[i code smells].
          p.mb-0 En un contexto de formación profesional, la aplicación de pruebas estáticas resulta vital para fomentar la disciplina y el trabajo colaborativo. Por ejemplo, puede pensarse en un equipo de aprendices del SENA que diseña un aplicativo web para la gestión de inventarios de una biblioteca. Antes de escribir la primera línea de código en HTML o #[i JavaScript], el equipo realiza una inspección formal del documento de requerimientos. Durante esta revisión, se detecta que el requerimiento “El sistema debe permitir préstamos rápidos” es ambiguo, ya que no define qué constituye “rápido” ni establece parámetros de tiempo o de interfaz. Al identificar y documentar este hallazgo mediante una prueba estática, el equipo corrige la especificación y evita desarrollar una funcionalidad que, posteriormente, no cumpliría con las expectativas del usuario final.
        .col-sm-12.col-lg-4.d-none.d-lg-block
          img(src='@/assets/curso/temas/t1/7.png', alt='')
      
      .titulo-sexto.color-acento-contenido(data-aos="fade-right")
        h5 Figura 1. 
        span Diagrama de flujo comparativo del costo de corrección de defectos: pruebas estáticas vs. Producción
      .row.justify-content-center.mb-5(data-aos="fade-right")
        .col-sm-12.col-lg-9
            figure.mb-0
              img(src='@/assets/curso/temas/t1/8.svg', alt='Diagrama de flujo comparativo sobre la corrección de defectos en dos momentos del desarrollo de software. A la izquierda se presenta la fase de requerimientos como corrección preventiva, donde el defecto se detecta de forma temprana mediante pruebas estáticas. Esta ruta incluye análisis y corrección inmediata de documentos, prevención de errores de codificación, menor esfuerzo de reingeniería y bajo costo, con ahorro de tiempo y recursos. A la derecha se presenta la fase de producción como corrección reactiva, donde el defecto se detecta cuando el sistema ya está en uso. Esta ruta implica identificación y depuración compleja de código, ciclos extensos de codificación y pruebas de regresión, integración y despliegue de parches, con costo alto, interrupción del servicio y daño reputacional. En la parte inferior se resume que las pruebas estáticas aportan valor preventivo mediante mayor calidad temprana, mitigación temprana de riesgos y ahorro significativo de recursos, mientras que las fallas en producción generan correcciones complejas y costosas, impacto negativo en usuarios y negocio, y retrasos significativos en el proyecto.')

      .cajon.color-acento-contenido.p-4.mb-0(data-aos="fade-right")
        p.mb-0 Esta práctica de revisión temprana se alinea directamente con el resultado de aprendizaje de implementar pruebas de acuerdo con procedimientos técnicos, demostrando que la calidad se construye desde la planeación. Las pruebas estáticas instauran una cultura de prevención, donde la meticulosidad en el análisis documental se convierte en la base para un desarrollo de #[i software] robusto y libre de defectos estructurales.
              
      Separador
      #t_1_2.titulo-segundo.color-acento-contenido(data-aos='fade-right')
        h2 1.2 Pruebas de caja negra y caja blanca
      
      
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5.br-1(data-aos="fade-right")
        .bloque-texto-g__img.d-none.d-lg-block(
          :style="{'background-image': `url(${require_src('@/assets/curso/temas/t1/9.png')})`}"
        )
        .bloque-texto-g__texto.p-4.d-flex.flex-column.justify-content-center.br-2
          p.mb-3 Las pruebas de caja negra, también conocidas como pruebas basadas en la especificación o pruebas funcionales, evalúan el comportamiento del #[i software] desde una perspectiva externa, ignorando por completo la arquitectura o el código fuente subyacente. En este enfoque, el sistema es visto como una “caja negra”, donde el evaluador proporciona datos de entrada, conocidos como #[i inputs], y verifica que los datos de salida, conocidos como #[i outputs], coincidan con los resultados esperados según los requerimientos del cliente.
          p.mb-0 La relevancia de este método radica en su capacidad para validar la experiencia final del usuario y asegurar que las funcionalidades del sistema operen de manera congruente con las necesidades de negocio. Desde una perspectiva instruccional, ejecutar pruebas de caja negra requiere adoptar la mentalidad del usuario final, dejando de lado los conocimientos técnicos sobre cómo está programado el sistema.
      
      
      p.mb-5(data-aos="fade-right") El diseño de estas pruebas implica la creación de escenarios y casos de uso basados exclusivamente en manuales, historias de usuario o especificaciones funcionales. Para optimizar este proceso y evitar la ejecución de un número excesivo de pruebas, se emplean técnicas de diseño formales como la partición de clases de equivalencia, que consiste en agrupar datos de entrada que deben generar el mismo comportamiento, y el análisis de valores límite, que permite probar los extremos numéricos o lógicos donde es más probable que ocurran errores.
      
      .row.justify-content-center.mb-5(data-aos="fade-right")
        .col-sm-12.col-lg-7.mx-0.px-0
          .bg-color-2.p-5.text-white
            p.mb-4 Para ilustrar este concepto en un escenario aplicable, puede considerarse el desarrollo de una plataforma de comercio electrónico para artesanos locales. El sistema posee un campo de texto para ingresar la cantidad de productos a comprar, el cual, según los requerimientos, solo debe aceptar números enteros entre 1 y 50. Aplicando la técnica de análisis de valores límite en una prueba de caja negra, no se revisa si el código usa un ciclo #[i if] o un #[i switch]; en su lugar, se ejecutan casos de prueba ingresando los valores 0, como límite inferior inválido; 1, como límite inferior válido; 50, como límite superior válido; y 51, como límite superior inválido. Si al ingresar 51 el sistema permite la compra en lugar de arrojar un mensaje de error, la prueba se registra como fallida.
            p.mb-2 Este tipo de pruebas asegura que la interfaz interactúe correctamente, que los flujos de navegación sean lógicos y que las restricciones operativas se cumplan a cabalidad, validando así el valor real que el producto tecnológico entrega a la sociedad.
        .col-sm-12.col-lg-5.d-none.d-lg-block.mx-0.px-0
          img(src='@/assets/curso/temas/t1/10.png', alt='')
      
      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Técnicas aplicadas en pruebas de caja negra

      .row.justify-content-center.mb-5(data-aos="fade-right")
        .col-sm-12.col-lg-3.d-none.d-lg-block
          img(src='@/assets/curso/temas/t1/11.png', alt='')
        .col-sm-12.col-lg-9
          TabsA.color-acento-botones
            .tarjeta.bg-color-3.p-4(titulo="Perspectiva externa")
              p.mb-0 Las pruebas de caja negra validan el comportamiento del sistema desde la experiencia del usuario, sin revisar la estructura interna del código.
            .tarjeta.bg-color-3.p-4(titulo="<i>Inputs y outputs</i>")
              p.mb-0 El evaluador ingresa datos de entrada y verifica que las salidas coincidan con los resultados esperados según los requerimientos.
            .tarjeta.bg-color-3.p-4(titulo="Partición de equivalencia")
              p.mb-0 Agrupa datos de entrada que deberían generar el mismo comportamiento, para reducir la cantidad de pruebas sin perder cobertura funcional.
            .tarjeta.bg-color-3.p-4(titulo="Valores límite")
              p.mb-0 Evalúa los extremos permitidos o no permitidos por el sistema, porque allí suelen presentarse errores con mayor frecuencia.
            .tarjeta.bg-color-3.p-4(titulo="Ejemplo aplicado")
              p.mb-0 En una compra con rango permitido entre 1 y 50 productos, se prueban valores como 0, 1, 50 y 51 para validar límites válidos e inválidos.

      .row.justify-content-center.mb-5.align-items-end(data-aos="fade-right")
        .col-sm-12.col-lg-9.bg-color-1.pcus-1
            p.mb-3 Las pruebas de caja blanca, también llamadas pruebas estructurales, de caja de cristal o de caja transparente, se enfocan en la anatomía interna del #[i software]. Este enfoque requiere conocimiento profundo y detallado del código fuente, la arquitectura de la base de datos, los algoritmos y los flujos de control de la aplicación.
            p.mb-0 El objetivo principal de las pruebas de caja blanca es verificar la estructura interna del sistema, asegurando que todas las rutas de código posibles, las condiciones lógicas y los bucles operen de manera eficiente, segura y sin errores ocultos. A diferencia de las pruebas de caja negra, aquí no solo interesa comprobar qué resultado entrega el sistema, sino cómo llega a ese resultado.
        .col-sm-12.col-lg-3.d-none.d-lg-block
          img(src='@/assets/curso/temas/t1/12.png', alt='')

      .cajon.color-acento-contenido.p-4.mb-5(data-aos="fade-right")
        p.mb-3 El proceso de realizar pruebas de caja blanca es altamente técnico y requiere bases sólidas en programación. Pedagógicamente, puede explicarse como la validación de la “tubería interna” de la aplicación. Mientras la caja negra verifica si sale agua limpia por el grifo, la caja blanca verifica que las tuberías no tengan fisuras, que las válvulas abran en el momento exacto y que no existan tramos inútiles, equivalentes al código muerto.
        p.mb-0 Las técnicas utilizadas en este nivel incluyen la cobertura de sentencias, que busca garantizar que cada línea de código se ejecute al menos una vez durante las pruebas; la cobertura de decisiones, que valida que las condiciones verdaderas y falsas sean evaluadas; y la cobertura de rutas, que permite probar los caminos lógicos posibles desde el inicio hasta el fin de un módulo.

      .row.justify-content-center.mb-5(data-aos="fade-right")
        .col-sm-12.col-lg-5.d-none.d-lg-block
          img(src='@/assets/curso/temas/t1/13.png', alt='')
        .col-sm-12.col-lg-1.d-none.d-lg-block
          img(src='@/assets/curso/temas/t1/14.svg', alt='')
        .col-sm-12.col-lg-6
            p.mb-0 Para comprender su aplicabilidad en la formación profesional, puede tomarse como ejemplo un sistema de información desarrollado por aprendices SENA que incluye un módulo de autenticación de usuarios, conocido como #[i login]. Al realizar pruebas de caja blanca sobre este módulo, se revisa directamente la función de validación escrita en lenguaje PHP o #[i Python]. Allí se analiza el bloque condicional que verifica si la contraseña coincide con el #[i hash] almacenado en la base de datos. También se diseña una prueba específica para forzar la ejecución de la cláusula #[i else] del código, es decir, el camino lógico que maneja el error de contraseña incorrecta, verificando además que no existan vulnerabilidades de inyección SQL en la consulta que interactúa con la base de datos.

      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Visualización de cobertura de rutas: pruebas de caja blanca
      
      ImagenInfografica.color-acento-botones.mb-4.bg-color-4.p-5.d-none.d-md-block(data-aos="fade-right")
        template(v-slot:imagen)
          figure
            img(src='@/assets/curso/temas/t1/15.png', alt='')
  
        .tarjeta.color-secundario.p-3(x="15%" y="38%" numero="1")
          .h5.mb-2 Diagrama de flujo de control
          p.mb-0 Representa las decisiones, condiciones y caminos que puede seguir el programa durante su ejecución.
        .tarjeta.color-secundario.p-3(x="50%" y="4%" numero="2")
          .h5.mb-2 Rutas posibles
          p.mb-0 Muestra los caminos que se pueden recorrer según las condiciones evaluadas en el código.
        .tarjeta.color-secundario.p-3(x="85%" y="37%" numero="3")
          .h5.mb-2 Casos de prueba
          p.mb-0 Relaciona combinaciones de entrada con las rutas que se ejecutan durante la prueba.
        .tarjeta.color-secundario.p-3(x="7%" y="88%" numero="4")
          .h5.mb-2 Porcentaje de cobertura
          p.mb-0 Permite identificar qué tanto del flujo lógico ha sido evaluado mediante los casos de prueba.
        .tarjeta.color-secundario.p-3(x="93%" y="88%" numero="5")
          .h5.mb-2 Calidad del código
          p.mb-0 Una mayor cobertura ayuda a detectar rutas no evaluadas, errores ocultos y debilidades en la lógica interna del #[i software].

      ImagenInfografica.color-acento-botones.mb-4.bg-color-4.p-5.d-block.d-md-none(data-aos="fade-right")
        template(v-slot:imagen)
          figure
            img(src='@/assets/curso/temas/t1/22.png', alt='')
  
        .tarjeta.color-secundario.p-3(x="18.5%" y="41%" numero="1")
          .h5.mb-2 Diagrama de flujo de control
          p.mb-0 Representa las decisiones, condiciones y caminos que puede seguir el programa durante su ejecución.
        .tarjeta.color-secundario.p-3(x="50.5%" y="19%" numero="2")
          .h5.mb-2 Rutas posibles
          p.mb-0 Muestra los caminos que se pueden recorrer según las condiciones evaluadas en el código.
        .tarjeta.color-secundario.p-3(x="81%" y="41.5%" numero="3")
          .h5.mb-2 Casos de prueba
          p.mb-0 Relaciona combinaciones de entrada con las rutas que se ejecutan durante la prueba.
        .tarjeta.color-secundario.p-3(x="27.5%" y="77.5%" numero="4")
          .h5.mb-2 Porcentaje de cobertura
          p.mb-0 Permite identificar qué tanto del flujo lógico ha sido evaluado mediante los casos de prueba.
        .tarjeta.color-secundario.p-3(x="73%" y="77.5%" numero="5")
          .h5.mb-2 Calidad del código
          p.mb-0 Una mayor cobertura ayuda a detectar rutas no evaluadas, errores ocultos y debilidades en la lógica interna del #[i software].
      .titulo-sexto.color-acento-contenido
        h5 Figura 2. 
        span Visualización de cobertura de rutas: pruebas de caja blanca
      .row.justify-content-center.mb-5
        .col-sm-12.col-lg-12
            figure.mb-0
              img(src='@/assets/curso/temas/t1/16.svg', alt='Infografía titulada Visualización de cobertura de rutas: pruebas de caja blanca. A la izquierda se presenta un diagrama de flujo de control con lectura inicial de variables, decisiones condicionales y dos rutas principales de procesamiento: ruta A y ruta B. El flujo permite representar los posibles caminos que puede seguir el programa según las condiciones evaluadas. A la derecha se muestran cuatro casos de prueba con sus respectivas combinaciones de entrada y la ruta cubierta en cada caso. En la parte inferior derecha aparece un resumen de cobertura de rutas, donde se comparan niveles de cobertura del 50 %, 75 % y 100 %, indicando cuántos casos de prueba se requieren para cubrir más caminos posibles. La infografía explica cómo las pruebas de caja blanca permiten evaluar la lógica interna del código, identificar rutas no cubiertas y mejorar la calidad total del software.')
            figcaption #[b Nota.] Elaboración propia con base en los principios de pruebas de #[i software] del #[i International Software Testing Qualifications Board] (ISTQB, 2024).

      p.mb-0(data-aos="fade-right") La integración de las pruebas de caja blanca en el perfil del egresado satisface el resultado de aprendizaje orientado a la implementación técnica. Fomenta un nivel de ingeniería de #[i software] más profundo, donde el desarrollador no solo se conforma con que el #[i software] funcione aparentemente bien, sino que garantiza que la lógica constructiva subyacente posea altos estándares de calidad, mantenibilidad y seguridad.








      Separador
      #t_1_3.titulo-segundo.color-acento-contenido(data-aos='fade-right')
        h2 1.3 Pruebas unitarias y aseguramiento desde el código
      
      p.mb-5(data-aos="fade-right") Las pruebas unitarias constituyen el nivel más granular y fundamental de las pruebas dinámicas de #[i software]. Su propósito es aislar y evaluar la unidad de código más pequeña comprobable de una aplicación, que generalmente corresponde a una función, un método o una clase específica, dependiendo del paradigma de programación utilizado. La filosofía detrás de las pruebas unitarias es verificar que cada pieza individual del rompecabezas funcione correctamente de manera independiente, antes de intentar ensamblar el sistema completo. Este tipo de pruebas son, por lo general, diseñadas, escritas y ejecutadas por los mismos desarrolladores durante la fase de codificación.    


      .row.justify-content-center.mb-5(data-aos="fade-right")
        .col-sm-12.col-lg-7.mx-0.px-0
          .bg-color-5.px-4.py-5
            p.mb-5 La enseñanza de las pruebas unitarias se aborda como una práctica de higiene en el desarrollo de #[i software]. No se trata simplemente de escribir código para probar código, sino de una metodología que estructura el pensamiento lógico. El proceso implica el uso de #[i frameworks] de automatización, como #[i JUnit] para #[i Java], #[i PyTest] para #[i Python] o #[i Jest] para #[i JavaScript], lo que permite que estas pruebas se ejecuten de manera rápida y repetitiva. Al estar automatizadas, proporcionan una red de seguridad: si se modifica una función existente para agregar una nueva característica, las pruebas unitarias permiten detectar de inmediato si ese cambio alteró el comportamiento original de la función, es decir, si generó una regresión.

            p.mb-2 A modo de ejemplo concreto, puede pensarse en el desarrollo de una función en #[i JavaScript] llamada calcularCostoEnvio(distancia, peso). Esta pequeña unidad de código debe retornar el valor del flete con base en dos parámetros matemáticos. Para realizar la prueba unitaria, se escribe un pequeño #[i script] de prueba utilizando el entorno #[i Jest], donde se afirma, mediante una validación o #[i assert], que, si la distancia es 10 km y el peso es 5 kg, la función debe retornar exactamente $15.000 COP. Si el código fuente tiene un error en la fórmula matemática, la prueba unitaria fallará de manera inmediata, localizando el error con precisión en esa función específica, sin necesidad de cargar la interfaz gráfica ni consultar bases de datos externas.
        .col-sm-12.col-lg-5.d-none.d-lg-block.mx-0.px-0
          img(src='@/assets/curso/temas/t1/17.png', alt='')


      p.mb-5(data-aos="fade-right") Al dominar las pruebas unitarias, el futuro profesional contribuye a que los cimientos técnicos de cualquier aplicativo sean robustos, escalables y confiables.
      .titulo-tercer-nivel.mb-5(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/bg/1.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Secuencia básica de una prueba unitaria

      .bg-full-width.bg-fondo-1(data-aos="fade-right")
        .p-full-width 
          .row.justify-content-center.mb-0
            .col-sm-12.col-lg-8
                LineaTiempoE.color-acento-contenido
                  .row(titulo="Paso 1")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t1/18.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Identificar la unidad
                      p.mb-0 Se selecciona la función, método o clase que será evaluada de forma aislada.
                  .row(titulo="Paso 2")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t1/19.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Definir datos de entrada
                      p.mb-0 Se establecen los valores que permitirán comprobar el comportamiento esperado de la unidad.
                  .row(titulo="Paso 3")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t1/20.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Ejecutar la validación
                      p.mb-0 Se utiliza un #[i framework] de pruebas para ejecutar la función y contrastar el resultado obtenido.
                  .row(titulo="Paso 4")
                    .col-lg-4.d-none.d-lg-block
                        img(src='@/assets/curso/temas/t1/21.svg')
                    .col-sm-12.col-lg-6.mb-4.mb-lg-0
                      h4 Analizar el resultado
                      p.mb-0 Se verifica si la salida coincide con el comportamiento esperado o si existe un error que requiere corrección.

          
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
