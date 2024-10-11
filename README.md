# Ejercicio B - Aplicación JavaFX de Gestión de Personas

Este proyecto es una aplicación de escritorio desarrollada en **JavaFX** para la gestión de una lista de personas. La aplicación permite agregar nuevas personas a una tabla con información de **nombre**, **apellido**, y **edad**.

## Características

- Añadir personas a una tabla.
- Verificación de datos antes de agregar (valida que los campos no estén vacíos y que la edad sea numérica).
- Mensajes de alerta para errores y éxito.
- Diseño de interfaz gráfico utilizando **FXML**.
- **JavaFX Properties** para hacer binding de datos entre el modelo y la vista.

  ## Estructura del Proyecto

### 1. Modelo

#### `Persona.java`

La clase `Persona` representa a una persona con las propiedades **nombre**, **apellido** y **edad**. Estas propiedades son observables gracias al uso de **JavaFX Properties**, lo que permite su uso en la interfaz gráfica para hacer binding con los controles de la vista.

### 2. Controlador

  ### HelloController.java

El controlador `HelloController` maneja la lógica de la aplicación. Es responsable de gestionar los eventos de la interfaz, como agregar una nueva persona a la tabla, verificar la validez de los datos y mostrar alertas de éxito o error.

### 3. Aplicación

  ### HelloApplication.java

La clase `HelloApplication` es la clase principal de la aplicación que extiende de JavaFX Application. Carga el archivo FXML que define la interfaz gráfica y establece los parámetros de la ventana, como el título y el tamaño mínimo.

### 4. Archivo FXML

El archivo FXML `ejercicioB.fxml` define la interfaz de usuario en un GridPane con un formulario para ingresar los datos de una persona (nombre, apellido y edad) y una tabla para mostrar las personas agregadas. Incluye TextField, Label y Button, así como una TableView para listar los datos.
