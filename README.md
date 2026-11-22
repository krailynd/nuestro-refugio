# Nuestro Refugio 🏠✨
### Calendario de Adviento, Música, Cartas y Cuaderno para Francesca & Elvis

Aplicación móvil Android desarrollada en **Kotlin** y **Jetpack Compose** con Material 3, arquitectura offline-first y sincronización en tiempo real vía GitHub API.

---

## 💖 Historia y Dedicatoria
- **Para:** Francesca (*Mio Principessa, Luna, Frambuesa, Mora, Blanquita*).
- **De:** Elvis (*Tu Sol y Rata Aspirable*).
- **Nuevo Comienzo:** Viernes 6 de noviembre de 2026 a las 18:18:35 PM (`2026-11-06T18:18:35-05:00`).

---

## 🌟 Módulos de la Aplicación

1. **🏠 La Casa de Adviento**:
   - Fachada invernal interactiva con 24 ventanas nevadas.
   - Cada tarde a las 6:00 PM (hora de Ica, Perú) se enciende una ventana con un minijuego y una pista del misterio.
2. **🔍 El Cuaderno del Admirador Secreto**:
   - 23 pistas caligráficas para descubrir quién deja los detalles en el edificio.
3. **🎧 El Refugio Musical**:
   - 13 canciones y melodías originales organizadas en 4 playlists:
     - *💖 Música Dulce*
     - *❤️ Música Amor*
     - *🎄 Música Navideña*
     - *🔥 Música Pasión*
   - Reproductor con ecualizador animado, carátulas en alta resolución y pausa automática de la música ambiental.
4. **💌 La Galería de Cartas**:
   - Cartas románticas con sello de lacre rojo carmesí `E ♥ F`.
   - Cartas bloqueadas con acertijos cómplices que solo Francesca puede descifrar.
   - Reacciones en tiempo real sincronizadas con el Panel Espejo del Creador.
5. **📖 Nuestro Cuaderno Compartido (Notion-style)**:
   - Bloc de notas compartido para metas, lista de películas para ver abrazados, rutas en Ica y recetas caseras.
   - Listas de tareas (To-Do) interactivas con casillas de verificación.

---

## 🔄 Canales de Sincronización en Tiempo Real
Los datos de la app se sincronizan de forma transparente mediante GitHub REST API / Raw Content:
- `data/letters.json`: Cartas de Elvis para Francesca.
- `data/vouchers.json`: Vales caseros con pistas misteriosas.
- `data/progress_sync.json`: Progreso en vivo de ventanas y reacciones.
- `data/our_notebook.json`: Cuaderno compartido.
