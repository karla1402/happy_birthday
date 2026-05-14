# Happy Birthday Joel

Una experiencia web interactiva y personalizada creada con amor para celebrar un cumpleaños especial.

## Características

Este proyecto es una "tarjeta virtual" interactiva que guía al usuario a través de tres pantallas llenas de detalles y animaciones:

1.  **El Sobre Mágico**: Un sobre interactivo que se abre al hacer clic, simulando la entrega de una carta física.
2.  **El Correo del Corazón**: Una interfaz que imita un correo electrónico con un mensaje tierno y directo.
3.  **La Gran Sorpresa**: Una escena festiva final que incluye:
    - **Banderines animados** que decoran la parte superior.
    - **Fotografía personalizada** con efectos de flotación y rotación.
    - **Carta detallada** con un diseño elegante y legible.
    - **Efectos visuales**: Explosiones de confeti y globos de colores que flotan hacia arriba.
    - **Interacción dinámica**: El confeti se activa automáticamente al llegar al final de la carta.

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica para una mejor organización del contenido.
- **CSS3**: Estilos personalizados, gradientes modernos y animaciones fluidas (`keyframes`).
- **JavaScript (Vanilla)**: Lógica de navegación entre pantallas y gestión de eventos.
- **[Canvas Confetti](https://www.joshwcomeau.com/snippets/javascript/canvas-confetti/)**: Biblioteca ligera para los efectos de celebración.
- **Google Fonts**: Uso de las tipografías _Outfit_ y _Caveat_ para un toque moderno y artesanal.

## Cómo usar

1.  Clona este repositorio o descarga los archivos.
2.  Asegúrate de tener tus imágenes en la carpeta `images/`:
    - `pastel.png` (favicon)
    - `sobre.png` (corazón del sobre)
    - `myLove.png` (foto principal)
    - `banderas.png` (decoración superior)
3.  Abre el archivo `index.html` en cualquier navegador moderno.

## Personalización

Si quieres adaptar este proyecto para alguien más, puedes modificar:

- **El nombre**: Cambia "Joel" en el `index.html`.
- **El mensaje**: Edita el texto dentro de `<div class="birthday-message">`.
- **Las fotos**: Reemplaza los archivos en la carpeta `images/` manteniendo los nombres o actualizando las rutas en el código.
