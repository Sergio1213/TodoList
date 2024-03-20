# Aplicación de Lista de Tareas en React

### Visión General

Esta aplicación de Lista de Tareas está construida utilizando React, una popular biblioteca de JavaScript para construir interfaces de usuario. Ayuda a los usuarios a gestionar sus tareas de manera efectiva al permitirles crear, editar y eliminar tareas según sea necesario.

### Componentes

#### Todo

El componente `Todo` representa un elemento de tarea individual en la lista de tareas. Contiene las siguientes características:

- Visualización del título de la tarea.
- Botón de edición para modificar el contenido de la tarea.
- Botón de eliminación para quitar la tarea de la lista.

#### TodoForm

El componente `TodoForm` es responsable de proporcionar una interfaz de formulario a los usuarios para agregar nuevas tareas a la lista de tareas. Incluye:

- Campo de entrada para ingresar el título de la tarea.
- Botón de envío para agregar la tarea a la lista.

#### TodoList

El componente `TodoList` es el contenedor de todos los elementos de la lista de tareas. Administra la visualización y funcionalidad de toda la lista, incluyendo:

- Renderizado de los componentes `Todo` individuales.
- Paso de funciones para manejar la edición y eliminación

### Uso

Para ejecutar esta aplicación de Lista de Tareas localmente, sigue estos pasos:

1. Clona el repositorio en tu máquina local.
2. Navega al directorio del proyecto en tu terminal.
3. Ejecuta `npm install` para instalar las dependencias.
4. Ejecuta `npm start` para iniciar el servidor de desarrollo.
5. Abre tu navegador y visita `http://localhost:3000` para ver la aplicación.
