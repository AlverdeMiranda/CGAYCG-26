# Registro de Desarrollo: Arte Cinético y Lumínico (Inspirado en Gyula Kosice)

## Contexto General del Proyecto
Desarrollo de un proyecto de arte digital y cinético inspirado en la obra de Gyula Kosice, específicamente en sus "Relieves Lumínicos". El objetivo es traducir los principios del arte Madí y los conceptos fundamentales de Kosice —geometría irregular, efectos lumínicos (neón), hidrogénesis y planos articulados— a un formato digital e interactivo mediante programación algorítmica.

## Rol y Personalidad del Agente
* **Identidad:** Experto en Arte Cinético, integrante virtual del Movimiento Madí y Desarrollador Senior en p5.js.
* **Enfoque:** Técnico y pedagógico. Toda decisión algorítmica será explicada a detalle para asegurar la comprensión de sus fundamentos de programación y su correlato con la teoría estética y conceptual.
* **Capacidades Integradas (Skills):**
  * `algorithmic-art`: Especialista en matemáticas de fluidos, partículas y geometría sagrada/cinética.
  * `high-end-visual-design`: Experto en efectos de iluminación neón, post-procesamiento de color y estética de lujo/museo.
  * `ui-ux-pro-max-skill`: Especialista en feedback interactivo y micro-interacciones fluidas.

## Restricciones de Trabajo Operativas
* **PROHIBIDO EJECUTAR:** No se debe escribir código en archivos de programación (como `.js`), ni crear estructuras de carpetas adicionales, ni tomar decisiones técnicas por el momento.
* **PAUSA DE SEGURIDAD:** Tras realizar tareas documentales o de inicialización, el agente debe detenerse por completo. No se avanzará ni se propondrán soluciones sin una orden o confirmación explícita del usuario.
* **EXPLICACIÓN PREVIA:** Cuando comience la fase de programación, cada bloque o fragmento de código deberá ir acompañado de una justificación. Se debe explicar por qué se eligió esa solución técnica y cómo se relaciona con los fundamentos estéticos de Kosice (neón, planos articulados, hidrogénesis).
* **ACTUALIZACIÓN CONTINUA:** Este archivo servirá como bitácora y se actualizará progresivamente cada vez que haya un avance o una nueva instrucción.

## Paso a Paso (Índice)
* [x] **Fase 1: Estructura de Relieves Lumínicos Hidrocinéticos**
  * [x] Composición y Grilla 3x3 con desplazamientos orgánicos.
  * [x] Geometría volumétrica: Medios cilindros con arcos y degradados.
  * [x] Iluminación y Color: Paleta Madí, canal Alpha y resplandor neón (`shadowBlur`).
  * [x] Detalles y Contenido: Hidrogénesis interna (burbujas) y puntos de anclaje externos.
* [x] **Fase 1.5: Precisión Estética de Matrices LED**
  * [x] Refactorización de pines a matrices ortogonales estrictas, emulando la obra real.
* [x] **Fase 2: Reestructuración Geométrica y Ortogonalidad**
  * [x] Distribución en grilla de líneas paralelas (sin colisiones).
  * [x] Proporción exacta 50/50 (verticales y horizontales).
  * [x] Corrección de perspectiva volumétrica (rectángulos frontales + luz cilíndrica).
* [x] **Fase 2.5: Ajustes Finos de Matriz y Color**
  * [x] Forzar cantidad par máxima (10 cilindros) para asegurar 50% de ejes.
  * [x] Variación 50/50 de conjuntos de matrices LED (grandes centradas vs chicas alineadas).
  * [x] Incorporación de color celeste neón puro a la paleta Madí.
* [x] **Fase 2.6: Formato Fijo y Paleta Completa**
  * [x] Lienzo con dimensiones fijas de museo (640x480) y centrado.
  * [x] Paleta cromática idéntica a las obras originales (inclusión de blanco puro).
  * [x] Variación del 50% en el diámetro físico de los LEDs (4.5px vs 3px).
* [x] **Fase 2.7: Ajustes de Realismo y Proporción Constante**
  * [x] Cilindros con ancho (grosor) constante, idéntico en todos los bloques.
  * [x] Burbujas hiperrealistas con reflejos especulares complejos.
  * [x] Inversión del fondo de página a blanco, manteniendo el canvas como marco negro.
* [x] **Fase 2.8: Confinamiento Estricto de Grilla (Cero Colisiones)**
  * [x] Contención matemática de las matrices LED para que no excedan su propia celda.
  * [x] Refuerzo de las líneas paralelas invisibles mediante márgenes rígidos.
* [x] **Fase 3: Interactividad y Comportamiento Cinético**
  * [x] **Temblor Lumínico (Click Izquierdo):** Vibración caótica de los cilindros de neón.
  * [x] **Temblor Eléctrico (Barra Espaciadora):** Vibración individual de la matriz de puntos LED.
  * [x] **Contracción (Tecla 0):** Acortamiento dinámico del eje principal de los bloques.
  * [x] **Hidrogénesis Continua (Tecla K):** Flujo de burbujas en bucle con persistencia.
* [x] **Fase 4: Cristalización de Obra Única**
  * [x] Inyección de `randomSeed` para fijar la estructura matemática.
  * [x] Garantía algorítmica de espectro completo (2 cilindros por cada uno de los 5 colores Madí).
* [x] **Fase 5: Interacción por Micrófono y Audio (Iteración 5 - Filtro de Ruido e Insonorización)**
  * [x] Creación de copia de respaldo de la versión funcional anterior en `sketch_backup_v1.js`.
  * [x] Ajuste de frecuencias a rangos audibles estándar (silbido, siseo "Ssss" y zumbido "Mmmm") para evitar la limitación física por hardware de micrófonos de laptop.
  * [x] Implementación de regla de prioridad de voz: si las burbujas están activas tras decir "gluglu" (por 4 segundos), se suprime y deshabilita la detección de silbidos, siseos y zumbidos.
  * [x] Implementación de un filtro de ruido de banda ancha (Wide-band Noise Detector): si se detecta energía en dos o más bandas de frecuencia simultáneamente (típico de roces de mouse, tecleo o golpes), el input se considera ruido ambiental y se ignora por completo.
  * [x] Incremento de los umbrales mínimos de volumen (de 12 a 40 para baja amplitud; de 100 a 140 para alta amplitud; y de 75 a 95 para picos de voz) para ignorar el ruido de fondo habitual de la habitación.
  * [x] Mapeo de silbido agudo (1000-2000 Hz) con duración de 1 a 2 segundos a vibración de cilindros de neón (Versión previa).
  * [x] Mapeo de siseo suave "Ssss" (3000-8000 Hz) con duración de 1 a 2 segundos a vibración de pines LED (Versión previa).
  * [x] Mapeo de zumbido grave suave "Mmmm" (100-250 Hz) a contracción de cilindros en tiempo real (Versión previa).
* [x] **Fase 6: Calibración Definitiva Sónica 1-a-1 y Exclusión Estricta**
  * [x] Modificación de las guías de texto del overlay de inicio para sincronizar las instrucciones visuales con la lógica sónica real.
  * [x] Mapeo sónico 1-a-1 final e individual:
    1. **Silbido agudo (1000-2000 Hz):** Contracción de los cilindros en tiempo real. Retorno elástico al silenciar sin vibración.
    2. **Siseo "Ssss" (3000-8000 Hz) de 1 a 2s:** Vibración de los cilindros (Neón) por 2 segundos tras finalizar el sonido.
    3. **Grave fuerte "Mmmm" (100-250 Hz) de 1 a 2s:** Vibración de las luces LED (pines) por 2 segundos tras finalizar el sonido.
    4. **Palabra "gluglu" (Voz o patrón rítmico):** Movimiento de burbujas (Hidrogénesis) por 4 segundos, desactivando cualquier otro disparador de forma exclusiva.
  * [x] Verificación en vivo en puerto local `http://localhost:8080/`.
* [x] **Fase 6.1: Depuración Sónica Visual y Filtro Inteligente**
  * [x] Diseño y renderización de un panel flotante de depuración en tiempo real en la esquina del lienzo para monitorizar los niveles individuales de cada entrada de audio frente a sus umbrales.
  * [x] Habilitación de la tecla 'D' para mostrar/ocultar el panel de depuración.
  * [x] Refinamiento del filtro de ruido de banda ancha: ahora ignora el bloqueo si detecta que un tono sónico (como silbido o grave) es claramente dominante frente a las otras frecuencias.
  * [x] Aumento de la sensibilidad del disparador de burbujas ("gluglu") al reducir el umbral vocal de 95 a 80 y omitir el filtro de ruido para la voz (dada su naturaleza multibanda).
* [x] **Fase 6.2: Ajuste Fino de Umbrales Sónicos**
  * [x] Separación de la constante global `AMPLITUDE_HIGH` en dos umbrales modulares: `THRESHOLD_SILBIDO` (130) y `THRESHOLD_GRAVE` (200).
  * [x] Reducción del umbral de silbidos a 130 para mejorar la respuesta ante silbidos más suaves o de menor intensidad.
  * [x] Elevación del umbral de graves a 200 para evitar que la vibración de los pines LED (puntos blancos) se active erróneamente por armónicos graves producidos por el habla o al pronunciar "gluglu".
  * [x] Actualización del panel de depuración visual de la pantalla para reportar y comparar la energía sónica actual con estas nuevas metas.
* [x] **Fase 6.3: Calibración de Graves a 190 y Liberación de Siseo**
  * [x] Ajuste fino del umbral `THRESHOLD_GRAVE` de 200 a 190, logrando un equilibrio óptimo de sensibilidad e insonorización.
  * [x] Eliminación de la constante restrictiva `AMPLITUDE_LOW_MAX` (120) para el siseo. Ahora el sistema detecta de forma fluida siseos tipo "Ssss" fuertes o realizados cerca del micrófono, requiriendo únicamente superar el piso `THRESHOLD_SISEO` (40) por 1-2s.
  * [x] Sincronización del panel de depuración visual para mostrar el nuevo objetivo de graves (190) y siseo (40).
