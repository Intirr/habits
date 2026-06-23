# Diario personal · BYMCYL

Un **diario personal** todo en uno: resumen del día, hábitos, bitácora, notas,
lecturas, recordatorios, progreso y finanzas. Personalizable y con toda la interfaz
editable. Es un único archivo HTML sin dependencias ni build: ábrelo en cualquier
navegador (`diario-personal.html`) y listo. Tus datos se guardan automáticamente en el
navegador (`localStorage`).

> ¿Prefieres inglés? Hay una versión equivalente en `personal-diary.html`, con sus propios
> datos (no se mezclan con los de la versión en español).

## Características

- **Diez vistas (pestañas):** **«Inicio»** (resumen del día), **«Hábitos»** (rutina del
  día), **«Sistemas»** (las acciones para cada hábito), **«Bitácora»** (ánimo, enfoque y
  diario), **«Notas»** (ideas y planes), **«Lecturas»** (libros en curso),
  **«Recordatorios»** (actividades programadas, con contador de pendientes), **«Progreso»**
  (metas semanales/mensuales, reflexión semanal, historial y rachas), **«Finanzas»**
  (ingresos, gastos, estado de la cuenta, alcancías y metas) y **«Personalizar»** (contenido,
  colores y edición de la interfaz).
- **Inicio / Resumen del día:** un panel de inicio con un saludo y seis tarjetas que
  resumen tu día y enlazan a cada sección: progreso de hábitos de hoy, ánimo y top 3,
  recordatorios pendientes (y vencidos), lectura actual, saldo de la cuenta y próxima meta, y tu racha
  con las estadísticas de la semana.
- **Bitácora del día:** combina tres rutinas de reflexión en una pestaña por día:
  - **Ánimo del día:** registra cómo te sientes (1–5 con caritas) y mira una mini
    tendencia de los últimos 30 días.
  - **Enfoque del día (top 3):** define entre 1 y 3 prioridades para el día y márcalas.
  - **Bitácora:** preguntas guiadas — cómo estuvo el día, una victoria, algo para mejorar
    o aprender, y gratitud.
  - En el calendario de Progreso, los días con entrada de bitácora llevan un puntito.
- **Hábitos con frecuencia:** cada hábito puede ser **diario** o en **días concretos**
  (p. ej. L–V, fin de semana o los días que elijas). El resumen del día solo cuenta los que
  tocan hoy. Además puedes **filtrar la lista por categoría (frente)** y **reordenar** los
  hábitos.
- **Indicador de hábitos sin hacer:** cada hábito muestra sus últimos 7 días con puntos —
  **verde** (hecho), **rojo** (tocaba y no lo hiciste) o tenue (pendiente o no tocaba). Al
  ver un día pasado, los hábitos que no cumpliste se marcan con un borde rojo y la etiqueta
  **«✗ sin hacer»**. Un día solo cuenta como «sin hacer» a partir de la primera vez que
  cumples ese hábito (los hábitos nuevos no se marcan).
- **Pensado para el móvil:** las pestañas se deslizan en una sola fila, las secciones y
  formularios se apilan, y los controles se adaptan a pantallas pequeñas.
- **Sistemas (acciones y procesos):** «no subes al nivel de tus metas, caes al nivel de tus
  sistemas». La pestaña **«Sistemas»** tiene dos partes:
  - **Sistemas por hábito:** para cada hábito diseñas la lista de **acciones concretas** que
    vas a emplear para hacerlo (añade, edita y quita pasos). Se guardan con cada hábito.
  - **Sistemas propios:** crea sistemas **independientes de los hábitos** —rutinas o procesos
    con su propio nombre y sus propias acciones (p. ej. «Rutina de mañana» o «Cierre del
    día»).
- **Metas semanales y mensuales:** en **«Progreso»**, separadas de los hábitos. Define una
  meta «X veces por semana o por mes», pulsa **«+ Hecho»** cada vez que la cumplas y mira tu
  progreso del periodo y tu **racha** por periodos.
- **Reflexión semanal:** dentro de **«Progreso»**, un repaso guiado de la semana (qué
  salió bien, qué mejorar, qué aprendiste y tu enfoque para la próxima), con navegación por
  semanas y un mini resumen (completados, días activos y ánimo medio).
- **Lecturas:** lleva el registro de los libros que lees. Anota título, autor y nº de
  páginas, marca tu página actual para ver el progreso, añade notas por libro y pásalo a
  «leído» cuando termines. Incluye estadísticas (leyendo, leídos y páginas leídas).
- **Notas (ideas y planes):** escribe notas con título y contenido; se ordenan por fecha,
  se guardan solas y puedes **buscarlas** con el buscador.
- **Descargar PNG en cada pestaña** (excepto Personalizar): genera una imagen con el estilo
  del diario de lo que ves — tu resumen, rutina, bitácora, notas, lecturas, recordatorios,
  progreso o finanzas.
- **Deshacer / Rehacer:** botones **«↶ Deshacer»** y **«↷ Rehacer»** (o `Ctrl/Cmd+Z` y
  `Ctrl/Cmd+Mayús+Z`) revierten cualquier cambio: marcar, editar, borrar, frecuencia,
  bitácora, reflexión, notas, lecturas, categorías, colores, recordatorios, finanzas, etc.
- **Recordatorios:** apunta actividades programadas con **fecha y hora**. Se ordenan por
  fecha, lo vencido se resalta, y puedes marcarlas como hechas, editarlas o borrarlas.
  La pestaña muestra un contador de pendientes.
- **Finanzas (cuenta + alcancías):** en la pestaña **«Finanzas»**, dos herramientas:
  - **Estado de la cuenta:** registra **ingresos** y **gastos** (tipo, concepto, cantidad y
    fecha) y mira tu **saldo**, total de ingresos y total de gastos. El saldo también aparece
    en la tarjeta de Inicio.
  - **Alcancías y metas:** crea **alcancías** para ahorrar y **metas de compra** con su precio
    objetivo; guarda o retira dinero y mira el progreso hacia cada objetivo. El símbolo de
    moneda es configurable.
- **Progreso (metas, historial y rachas):** reúne las **metas semanales/mensuales**, la
  **reflexión semanal** y un calendario de actividad por meses (estilo «contribuciones») con
  rango **Mes / 3 meses / 6 meses / Año** y estadísticas (racha actual, mejor racha, días
  activos, completados y constancia).
- **Estados vacíos con ejemplos:** cuando una sección está vacía (hábitos o notas), te
  ofrece **empezar con ejemplos** de un toque.
- **Tema de colores de la página:** cambia los colores de *toda* la página, no solo el
  acento. Hay **8 temas predefinidos** (Noche, Carbón, Medianoche, Bosque, Sepia, Vino,
  Claro, Niebla) y **selectores de color personalizados** para fondo, superficies, líneas,
  textos y títulos.
- **Interfaz 100% editable:** en la pestaña **«Personalizar»**, dentro de *Edición de la
  interfaz*, pulsa **«Editar interfaz»** y cambia *cualquier* texto: título, subtítulo,
  frase, **los nombres de las pestañas**, etiquetas, textos de botones, nombres de sección y
  el pie de página. Pulsa **«Listo»** para volver al modo de uso. «Restaurar textos»
  revierte los textos a los originales.
- **Categorías (frentes) personalizables:** crea, renombra, recolorea y elimina las
  categorías (vienen Cuerpo, Mente, Alma y Valor profesional como ejemplo).
- **Color de acento:** elige un preset o un color personalizado.
- **Hábitos con horario:** opcionalmente añade hora de inicio y fin.
- **Exportar / importar:**
  - **PNG** de cualquier pestaña (botón «📷 PNG»), más **texto** de la rutina de hábitos.
  - **Exportar datos** / **Importar datos** en `.json` para respaldar o mover tus datos
    entre dispositivos. El respaldo incluye **todo**: el título y la personalización de la
    interfaz, las categorías y colores, los hábitos y sus sistemas, las metas, la bitácora,
    las reflexiones, las lecturas, los recordatorios y las finanzas.
- **Restaurar ejemplo** y **Vaciar** para empezar de cero. **Vaciar** borra los hábitos,
  metas, historial y recordatorios, y **restablece** el título, las categorías, los colores
  y los textos de la interfaz a los originales.

## Uso

1. Abre `diario-personal.html` en tu navegador (o `personal-diary.html` para la versión en
   inglés).
2. **«Inicio»**: mira el resumen del día y salta a cualquier sección. **«Hábitos»**: marca
   los que cumplas hoy (cada uno con su frecuencia). **«Sistemas»**: diseña las acciones de
   cada hábito. **«Bitácora»**: registra tu ánimo, tu top 3 y tu diario del día.
   **«Notas»**: apunta ideas y planes (con buscador). **«Lecturas»**: lleva tus libros en
   curso. **«Recordatorios»**: actividades programadas con fecha y hora. **«Progreso»**:
   metas semanales/mensuales, reflexión semanal e historial y rachas. **«Finanzas»**:
   ingresos, gastos, estado de la cuenta, alcancías y metas. Todo se guarda solo (y puedes
   bajar un PNG de cada vista).
3. En la pestaña **«Personalizar»**: cambia título, categorías y colores (tema), y activa
   **«Editar interfaz»** para reescribir cualquier texto de la pantalla.
4. ¿Te equivocaste? Usa **«↶ Deshacer»** (o `Ctrl/Cmd+Z`).
5. Respalda con **«Exportar datos»** cuando quieras.

> Los datos viven en el navegador (`localStorage`). Si borras los datos del sitio o
> usas otro dispositivo, impórtalos desde tu respaldo `.json`.

---

*break your mind, change your life*
