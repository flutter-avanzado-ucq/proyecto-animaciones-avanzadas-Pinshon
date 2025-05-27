# tareas

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Animaciones y colores en la app de tareas

Esta app implementa animaciones y cambios visuales para mejorar la experiencia del usuario:

- **Cambio de color y opacidad**:  
  - Al crear una tarea, el contenedor es de color naranja.  
  - Al completar una tarea, el contenedor cambia a lila claro y su opacidad disminuye, indicando visualmente que ha sido completada.

- **Rotación y color del ícono**:  
  - El ícono de estado (check) solo gira 180° al marcar una tarea como completada.  
  - El ícono se vuelve azul cuando la tarea está completada.

- **Deslizamiento para eliminar**:  
  - Al deslizar una tarea hacia la izquierda, aparece un fondo rojo con el ícono de eliminar, indicando la acción de borrado.

- **AnimatedIcon en el FAB**:  
  - El botón flotante cambia entre los íconos de "agregar" y "evento" (calendario) al abrir el modal para agregar tareas, brindando un mejor feedback visual.

Estas animaciones y cambios de color ayudan a que la app sea más interactiva, fluida y fácil de usar.
