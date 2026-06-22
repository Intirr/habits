# Diario personal · BYMCYL

Un **diario personal** todo en uno: hábitos, notas, recordatorios, progreso y dinero.
Personalizable y con toda la interfaz editable. Es un único archivo HTML sin dependencias
ni build: ábrelo en cualquier navegador (`index.html`) y listo. Tus datos se guardan
automáticamente en el navegador (`localStorage`).

## Características

- **Seis vistas separadas (pestañas):** **«Hábitos»** (rutina del día),
  **«Notas»** (ideas y planes), **«Recordatorios»** (actividades programadas, con contador
  de pendientes), **«Progreso»** (metas, historial y rachas), **«Dinero»** (alcancías y
  metas) y **«Personalizar»** (contenido, colores y edición de la interfaz).
- **Descargar PNG en cada pestaña** (excepto Personalizar): genera una imagen con el estilo
  del diario de lo que ves — tu rutina, tus notas, recordatorios, progreso o dinero.
- **Notas (ideas y planes):** escribe notas con título y contenido; se ordenan por fecha y
  se guardan solas. Ideal para apuntar ideas sueltas o planes futuros.
- **Deshacer / Rehacer:** botones **«↶ Deshacer»** y **«↷ Rehacer»** (o `Ctrl/Cmd+Z` y
  `Ctrl/Cmd+Mayús+Z`) revierten cualquier cambio: marcar, editar, borrar, metas, notas,
  categorías, colores, recordatorios, dinero, etc.
- **Recordatorios:** apunta actividades programadas con **fecha y hora**. Se ordenan por
  fecha, lo vencido se resalta, y puedes marcarlas como hechas, editarlas o borrarlas.
  La pestaña muestra un contador de pendientes.
- **Dinero (alcancías y metas):** crea **alcancías** para ahorrar y **metas de compra**
  con su precio objetivo. Guarda o retira dinero en cada una y mira el progreso hacia la
  meta, con un resumen (ahorrado total, nº de alcancías, metas cumplidas y cuánto falta).
  El símbolo de moneda es configurable.
- **Hábitos diarios:** marca tus hábitos cada día; el progreso del día se muestra con una
  barra y un contador, y cada hábito lleva su racha 🔥 de días seguidos.
- **Progreso (metas + historial y rachas):** en su propia pestaña. Las **metas semanales y
  mensuales** van aquí, separadas de los hábitos diarios: define «X veces por semana/mes»,
  pulsa «Hecho» cada vez que la cumplas y mira tu progreso del periodo y tu racha por
  periodos. Debajo, un calendario de actividad por meses (estilo «contribuciones») con
  rango **Mes / 3 meses / 6 meses / Año** y estadísticas (racha actual, mejor racha, días
  activos, completados y constancia).
- **Tema de colores de la página:** cambia los colores de *toda* la página, no solo el
  acento. Hay **8 temas predefinidos** (Noche, Carbón, Medianoche, Bosque, Sepia, Vino,
  Claro, Niebla) y **selectores de color personalizados** para fondo, superficies, líneas,
  textos y títulos.
- **Interfaz 100% editable:** en la pestaña **«Personalizar»**, dentro de *Edición de la
  interfaz*, pulsa **«Editar interfaz»** y cambia *cualquier* texto: título, subtítulo,
  frase, etiquetas, textos de botones, nombres de sección y el pie de página. Pulsa
  **«Listo»** para volver al modo de uso. «Restaurar textos» revierte los textos a los
  originales.
- **Categorías (frentes) personalizables:** crea, renombra, recolorea y elimina las
  categorías (vienen Cuerpo, Mente, Alma y Valor profesional como ejemplo).
- **Color de acento:** elige un preset o un color personalizado.
- **Hábitos con horario:** opcionalmente añade hora de inicio y fin; la lista se ordena
  por hora.
- **Exportar / importar:**
  - **PNG** de cualquier pestaña (botón «📷 PNG»), más **texto** de la rutina de hábitos.
  - **Exportar datos** / **Importar datos** en `.json` para respaldar o mover tus datos
    entre dispositivos.
- **Restaurar ejemplo** y **Vaciar** para empezar de cero.

## Uso

1. Abre `index.html` en tu navegador.
2. **«Hábitos»**: marca los que cumplas hoy. **«Notas»**: apunta ideas y planes.
   **«Recordatorios»**: actividades programadas con fecha y hora.
   **«Progreso»**: metas semanales/mensuales más historial y rachas. **«Dinero»**:
   alcancías y metas de compra. Todo se guarda solo (y puedes bajar un PNG de cada vista).
3. En la pestaña **«Personalizar»**: cambia título, categorías y colores (tema), y activa
   **«Editar interfaz»** para reescribir cualquier texto de la pantalla.
4. ¿Te equivocaste? Usa **«↶ Deshacer»** (o `Ctrl/Cmd+Z`).
5. Respalda con **«Exportar datos»** cuando quieras.

> Los datos viven en el navegador (`localStorage`). Si borras los datos del sitio o
> usas otro dispositivo, impórtalos desde tu respaldo `.json`.

---

*break your mind, change your life*
