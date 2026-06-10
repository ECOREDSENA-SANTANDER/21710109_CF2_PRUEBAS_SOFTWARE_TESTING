<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      // Para cuestionario usar: <ActividadController :cuestionario="cuestionario"/>
      // Para parrafo usar: <ActividadController :parrafo="parrafo"/>
      #Actividad                
      <ActividadController :cuestionario="cuestionario"/>
  
  </template>

<script>
import ActividadController from '@ecored-sena/boulder-kit/plugin/components/actividad/ActividadController.vue'

export default {
  name: 'ActividadDidactica',
  components: {
    ActividadController,
  },
  data: () => ({
    cuestionario: {
      tema: 'Microcontroladores y sensores',
      titulo: 'Cuestionario',
      introduccion:
        '<b>Objetivo:</b> verificar la comprensión de los conceptos fundamentales relacionados con la ejecución de pruebas de <i>software</i>, la documentación de resultados, la gestión de incidentes y la formulación de planes de mejora.',
      barajarPreguntas: false,
      titulo_aprobado: '¡BUEN TRABAJO!',
      titulo_reprobado: 'VUELVA A INTENTARLO',
      preguntas: [
        {
          id: 1,
          texto:
            '¿Cuál es el propósito principal de las pruebas estáticas en un proyecto de <i>software</i>?',
          imagen: '@/assets/actividad/imagen1.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Ejecutar el sistema en producción.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Revisar artefactos sin ejecutar el código.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Reemplazar las pruebas dinámicas.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Validar únicamente la interfaz gráfica.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto:
            '¿Por qué la detección temprana de defectos reduce el costo de corrección?',
          imagen: '@/assets/actividad/imagen2.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Porque evita documentar los hallazgos.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Porque elimina toda necesidad de pruebas.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Porque permite corregir antes de producción.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Porque solo interviene el usuario final.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto: '¿Qué caracteriza a las pruebas de caja negra?',
          imagen: '@/assets/actividad/imagen3.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Evalúan entradas y salidas según requisitos.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Analizan directamente el código fuente.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Miden solo el rendimiento del servidor.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Se aplican sin casos de prueba definidos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Qué técnica de caja negra prueba los extremos de un rango permitido?',
          imagen: '@/assets/actividad/imagen4.png',
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Cobertura de sentencias.', esCorrecta: false },
            { id: 'b', texto: 'Depuración estructural.', esCorrecta: false },
            {
              id: 'c',
              texto: 'Revisión informal de código.',
              esCorrecta: false,
            },
            { id: 'd', texto: 'Análisis de valores límite.', esCorrecta: true },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto: '¿Qué requiere principalmente una prueba de caja blanca?',
          imagen: '@/assets/actividad/imagen5.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Ignorar la arquitectura del sistema.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Probar solo desde la perspectiva del cliente.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Conocer la lógica interna del código.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Validar únicamente mensajes visuales.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Qué busca comprobar la cobertura de decisiones en caja blanca?',
          imagen: '@/assets/actividad/imagen6.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Que los manuales estén completos.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Que cada condición se evalúe como verdadera y falsa.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Que el usuario acepte el diseño visual.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Que no existan requerimientos funcionales.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto: '¿Cuál es el propósito de las pruebas unitarias?',
          imagen: '@/assets/actividad/imagen7.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Evaluar una unidad pequeña de código de forma aislada.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Revisar solo documentos de requerimientos.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Ejecutar pruebas únicamente al final del proyecto.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Validar todas las funcionalidades con usuarios.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            '¿Qué ventaja ofrecen los <i>frameworks</i> de pruebas unitarias como JUnit, PyTest o Jest?',
          imagen: '@/assets/actividad/imagen8.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Evitan escribir código funcional.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Permiten ejecutar pruebas rápidas y repetitivas.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Sustituyen la matriz de trazabilidad.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Eliminan la documentación técnica.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto: '¿Cuándo un caso de prueba se registra como <i>fail</i> ?',
          imagen: '@/assets/actividad/imagen9.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Cuando coincide con el resultado esperado.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Cuando no se ejecuta ningún entorno.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Cuando el resultado real se desvía del esperado.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Cuando no existe evidencia digital.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            '¿Qué información debe incluir el registro de un hallazgo de prueba?',
          imagen: '@/assets/actividad/imagen10.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Fecha, entorno, datos de entrada y salida real.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Solo el nombre del evaluador.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Únicamente la opinión del usuario.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Solo el lenguaje de programación usado.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto:
            '¿Para qué se utiliza la matriz de trazabilidad de requerimientos?',
          imagen: '@/assets/actividad/imagen1.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Para eliminar los reportes de incidentes.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Para vincular requerimientos con casos de prueba.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Para reemplazar las pruebas de caja negra.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Para ocultar defectos no reproducibles.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 12,
          texto: '¿Qué permite cuantificar la cobertura de pruebas?',
          imagen: '@/assets/actividad/imagen2.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'El alcance del esfuerzo de evaluación realizado.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'El diseño gráfico de la aplicación.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'La cantidad de usuarios registrados.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'La velocidad de conexión del equipo.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 13,
          texto: '¿Cómo se calcula de forma básica la cobertura de pruebas?',
          imagen: '@/assets/actividad/imagen3.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Elementos totales por elementos no evaluados.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Errores encontrados menos casos exitosos.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Elementos evaluados divididos entre el total por cien.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Casos fallidos divididos entre usuarios activos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 14,
          texto: '¿Por qué es importante el análisis de impacto y completitud?',
          imagen: '@/assets/actividad/imagen4.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Porque todos los módulos tienen la misma criticidad.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Porque reemplaza la validación funcional.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Porque evita calcular métricas de cobertura.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Porque orienta pruebas hacia áreas de mayor riesgo.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 15,
          texto: '¿Qué debe contener un reporte de error efectivo?',
          imagen: '@/assets/actividad/imagen5.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Título, severidad, prioridad, entorno y pasos para reproducir.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Solo capturas sin descripción.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Comentarios generales sin evidencia.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Únicamente el nombre del programador.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 16,
          texto: '¿Qué ocurre cuando un defecto corregido vuelve al evaluador?',
          imagen: '@/assets/actividad/imagen6.png',
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Se elimina sin revisión.', esCorrecta: false },
            {
              id: 'b',
              texto: 'Se ejecuta una prueba de confirmación.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Se ignora la evidencia previa.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Se registra automáticamente como nuevo.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 17,
          texto: '¿Cuál es la finalidad del informe de resumen de pruebas?',
          imagen: '@/assets/actividad/imagen7.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Compilar resultados para facilitar decisiones.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Sustituir los casos de prueba.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Ocultar incidentes menores.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Modificar los requerimientos sin aprobación.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 18,
          texto: '¿Qué indica una tasa alta de defectos rechazados?',
          imagen: '@/assets/actividad/imagen8.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Que el <i>software</i> no requiere pruebas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Que la cobertura siempre es del 100 %.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Que todos los reportes son críticos.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Que puede haber baja comprensión de requerimientos.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 19,
          texto:
            '¿Para qué se realiza la retrospectiva del proceso de pruebas?',
          imagen: '@/assets/actividad/imagen9.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Para sancionar al equipo de desarrollo.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Para identificar aprendizajes y oportunidades de mejora.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Para cerrar defectos sin validación.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Para evitar la socialización del conocimiento.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 20,
          texto: '¿Qué diferencia una acción preventiva de una correctiva?',
          imagen: '@/assets/actividad/imagen10.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'La preventiva elimina causas potenciales antes de que ocurran.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'La preventiva corrige únicamente errores ya reportados.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'La correctiva se aplica antes de identificar riesgos.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Ambas impiden documentar incidentes.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
    parrafo: {
      tema: 'Comprendiendo el diseño de presupuestos y estrategias de ahorro',
      titulo: 'Completar frases',
      introduccion:
        '<b>Objetivo:</b> verificar la comprensión de los conceptos fundamentales relacionados con la ejecución de pruebas de <i>software</i>, la documentación de resultados, la gestión de incidentes y la formulación de planes de mejora.',
      instruccion:
        'Complete correctamente los enunciados con la palabra que falta según los contenidos estudiados en el componente formativo.',
      imagen: '@/assets/actividad/imagen1.png',
      barajarPreguntas: true,
      textos: [
        {
          id: 1,
          texto:
            'El [respuesta] personal es una herramienta que permite proyectar ingresos y egresos para mantener la estabilidad económica.',
          respuesta: 'presupuesto',
        },
        {
          id: 2,
          texto:
            'La constancia en el cumplimiento del presupuesto refleja un alto nivel de [respuesta] financiera.',
          respuesta: 'disciplina',
        },
        {
          id: 3,
          texto:
            'Ahorrar no es lo que sobra, sino lo que se [respuesta] guardar antes de gastar.',
          respuesta: 'planifica',
        },
        {
          id: 4,
          texto:
            'Un gasto innecesario que puede eliminarse sin afectar la calidad de vida básica se denomina gasto [respuesta].',
          respuesta: 'discrecional',
        },
        {
          id: 5,
          texto:
            'La cultura del ahorro promueve el uso responsable de los [respuesta] disponibles.',
          respuesta: 'recursos',
        },
        {
          id: 6,
          texto:
            'El estado de [respuesta] personales permite analizar la relación entre ingresos y egresos en un periodo determinado.',
          respuesta: 'resultados',
        },
        {
          id: 7,
          texto:
            'Cuando los ingresos son mayores que los egresos se generan una [respuesta] que puede destinarse al ahorro.',
          respuesta: 'utilidad',
        },
        {
          id: 8,
          texto:
            'Uno de los beneficios de ejecutar un presupuesto es la reducción del [respuesta] financiero.',
          respuesta: 'estrés',
        },
        {
          id: 9,
          texto:
            'Evitar gastos impulsivos y mantener límites presupuestales refleja [respuesta] financiera.',
          respuesta: 'disciplina',
        },
        {
          id: 10,
          texto:
            'Contar con un fondo de [respuesta] permite enfrentar gastos inesperados sin afectar el presupuesto.',
          respuesta: 'emergencia',
        },
      ],
    },
  }),
}
</script>
