# Grid Dinámico de Videos con LocalStorage

Este proyecto es una aplicación web que permite agregar, visualizar y eliminar videos de YouTube utilizando `iframe`. Los videos se organizan automáticamente en un diseño de grid dinámico que se ajusta al número de videos y al tamaño de la pantalla. Los videos se guardan en el `localStorage` para que persistan entre sesiones.

## Características

- **Agregar videos**: Permite agregar videos de YouTube pegando el código del `iframe`.
- **Eliminar videos**: Cada video tiene un botón de eliminación para quitarlo del grid y del `localStorage`.
- **Grid dinámico**: El diseño del grid se ajusta automáticamente para aprovechar al máximo el espacio disponible.
- **Persistencia**: Los videos se guardan en el `localStorage` para que estén disponibles al recargar la página.

## Tecnologías utilizadas

- **HTML**: Estructura de la página.
- **CSS**: Estilo y diseño del grid.
- **JavaScript**: Lógica para agregar, eliminar y ajustar el grid dinámicamente.
- **LocalStorage**: Almacenamiento persistente de los videos.

## Cómo usar

### 1. Agregar un video
1. Copia el código del `iframe` de un video de YouTube.
2. Pega el código en el campo de texto que dice "Pega aquí el código del iframe".
3. Haz clic en el botón **"Agregar Iframe"**.
4. El video aparecerá en el grid y se guardará automáticamente en el `localStorage`.

### 2. Eliminar un video
1. Cada video tiene un botón rojo con una "X" en la esquina superior derecha.
2. Haz clic en el botón para eliminar el video.
3. El video se eliminará del grid y del `localStorage`.

### 3. Ajuste dinámico del grid
- El número de columnas y filas del grid se calcula automáticamente en función del número de videos.
- Ejemplo:
  - Si hay 4 videos, se organizan en 2 filas y 2 columnas.
  - Si hay 6 videos, se organizan en 2 filas y 3 columnas.
- El diseño se adapta automáticamente al tamaño de la pantalla.