# Tracker de hábitos · BYMCYL

Un tracker de hábitos **personalizable** con seguimiento diario, rachas e historial.
Toda la interfaz es editable. Es un único archivo HTML sin dependencias ni build:
ábrelo en cualquier navegador (`index.html`) y listo. Tus datos se guardan
automáticamente en el navegador (`localStorage`).

## Características

- **Seguimiento diario:** marca tus hábitos cada día. El progreso del día se muestra
  con una barra y un contador.
- **Objetivos semanales / mensuales:** además de los hábitos diarios, cada hábito puede
  tener una meta de **«X veces por semana»** o **«X veces por mes»** (pulsa el 🎯 del
  hábito). Verás una barra de progreso del periodo (ej. *2/3 esta semana*) y la racha 🔥
  se mide en el periodo correspondiente (días, semanas o meses seguidos cumpliendo la meta).
- **Rachas (streaks):** cada hábito muestra 🔥 con su racha; el panel calcula la racha
  actual y la mejor racha global.
- **Historial amplio:** calendario de actividad por meses (estilo «contribuciones») con
  rango seleccionable **Mes / 3 meses / 6 meses / Año**, además de una tira de 7 puntos
  por hábito. Toca cualquier día para revisarlo o completarlo (también con `‹ ›`).
- **Estadísticas:** racha actual, mejor racha, días activos, total de completados,
  constancia del rango y objetivos cumplidos.
- **Tema de colores de la página:** cambia los colores de *toda* la página, no solo el
  acento. Hay **8 temas predefinidos** (Noche, Carbón, Medianoche, Bosque, Sepia, Vino,
  Claro, Niebla) y **selectores de color personalizados** para fondo, superficies, líneas,
  textos y títulos.
- **Interfaz 100% editable:** pulsa **«Editar interfaz»** y cambia *cualquier* texto:
  título, subtítulo, frase, etiquetas, textos de botones, nombres de sección y el pie
  de página. Pulsa **«Listo»** para volver al modo de uso. «Restaurar textos» revierte
  los textos a los originales.
- **Categorías (frentes) personalizables:** crea, renombra, recolorea y elimina las
  categorías (vienen Cuerpo, Mente, Alma y Valor profesional como ejemplo).
- **Color de acento:** elige un preset o un color personalizado.
- **Hábitos con horario:** opcionalmente añade hora de inicio y fin; la lista se ordena
  por hora.
- **Exportar / importar:**
  - **PNG** y **texto** del día seleccionado (para compartir o imprimir).
  - **Exportar datos** / **Importar datos** en `.json` para respaldar o mover tus datos
    entre dispositivos.
- **Restaurar ejemplo** y **Vaciar** para empezar de cero.

## Uso

1. Abre `index.html` en tu navegador.
2. Marca los hábitos que cumplas hoy. Todo se guarda solo.
3. Personaliza con **«Personalizar»** (título, categorías, color) y con
   **«Editar interfaz»** (cualquier texto de la pantalla).
4. Respalda con **«Exportar datos»** cuando quieras.

> Los datos viven en el navegador (`localStorage`). Si borras los datos del sitio o
> usas otro dispositivo, impórtalos desde tu respaldo `.json`.

---

*break your mind, change your life*
