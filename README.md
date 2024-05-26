
![Captura de pantalla 2024-05-25 230219](https://github.com/FranJavacisco/Eventos-y-componentes-vue/assets/134477809/7a7aa16f-bcdf-4eab-848e-62e8414c50ea)

# Eventos y Componentes en VUE

## Descripción del Proyecto

Este proyecto consiste en desarrollar una aplicación interactiva para la gestión de citas médicas, utilizando el framework Vue.js. La aplicación permitirá a los usuarios registrar, visualizar y gestionar citas médicas de manera eficiente.

## Funcionalidades

### Formulario de Registro de Citas

- **Campos del Formulario:** 
  - Paciente
  - Fecha
  - Hora
  - Gravedad
  - Motivo

### Interacción del Usuario

- **Validación de Campos:** Los labels del formulario se mostrarán en color rojo mientras el campo correspondiente esté vacío. Una vez llenado el campo, el label volverá a su color natural (negro).
- **Botón de Agregar:** El botón de agregar cita se mantendrá deshabilitado hasta que todos los campos del formulario tengan un valor.

### Visualización de Citas

- **Mensaje Inicial:** Debajo del formulario, se mostrará un mensaje indicando que aún no hay consultas registradas hasta que se agregue la primera cita.
- **Renderización de Citas:** Al agregar una cita, los campos del formulario se limpiarán automáticamente. La información de cada cita se mostrará en un formato de tarjeta (card).

### Validación y Feedback

- **Colores según Gravedad:** Cada nivel de gravedad definida en las citas determinará el color de fondo de la tarjeta relacionada.
  - Baja: Verde
  - Media: Amarillo
  - Alta: Rojo

### Características Adicionales

- **Botón Eliminar:** Cada tarjeta de cita incluirá un botón de eliminar. Al hacer clic en este botón, se emitirá un evento al componente padre para eliminar la cita del arreglo de citas registradas.

## Tecnologías Utilizadas

- **Framework:** Vue.js
- **Herramienta de Construcción:** Vite
- **Lenguajes:** JavaScript, HTML, CSS

## Instrucciones para Ejecutar o Visualizar

### Configuración del Proyecto

1. Asegúrate de tener Node.js y npm instalados.
2. Clona este repositorio y navega a la carpeta del proyecto:
   ```sh
   git clone https://github.com/tu-usuario/mi-proyecto-vue.git
   cd mi-proyecto-vue
   ```

### Instalar Dependencias

3. Ejecuta `npm install` para instalar las dependencias:
   ```sh
   npm install
   ```

### Ejecutar el Servidor de Desarrollo

4. Utiliza `npm run dev` para iniciar el servidor de desarrollo:
   ```sh
   npm run dev
   ```

### Visualizar la Aplicación

5. Abre tu navegador y navega a [http://localhost:5173](http://localhost:5173) para visualizar la aplicación.

## Contribuir

¡Me encantaría contar con tu colaboración para mejorar este proyecto! Si tienes ideas para nuevas funcionalidades, mejoras en la interfaz, corrección de errores o cualquier otra sugerencia, no dudes en contribuir. Aquí tienes cómo puedes hacerlo:

### Fork del Repositorio

- Haz un fork de este repositorio para tener una copia en tu cuenta de GitHub.

### Clonar el Repositorio

- Clona el repositorio a tu máquina local:
  ```sh
  git clone https://github.com/tu-usuario/mi-proyecto-vue.git
  ```

### Crear una Rama para tu Funcionalidad

- Crea una nueva rama para trabajar en tu funcionalidad o corrección:
  ```sh
  git checkout -b nombre-de-tu-rama
  ```

### Realizar tus Cambios y Confirmar

- Realiza los cambios necesarios y confirma los cambios:
  ```sh
  git add .
  git commit -m "Descripción de tus cambios"
  ```

### Enviar tus Cambios

- Envía tus cambios a tu repositorio fork:
  ```sh
  git push origin nombre-de-tu-rama
  ```

### Crear un Pull Request

- Desde tu repositorio fork en GitHub, crea un pull request hacia el repositorio original.

¡Gracias por tu interés en contribuir! Espero tus pull requests y sugerencias para hacer de esta aplicación algo aún más increíble.
