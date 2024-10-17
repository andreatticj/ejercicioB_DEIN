# Ejercicio B - Aplicación JavaFX de Gestión de Personas

Este proyecto es una aplicación de escritorio desarrollada en JavaFX que permite gestionar una lista de personas. Los usuarios pueden agregar personas a una tabla y recibir notificaciones sobre la entrada de datos, asegurando que se mantenga la integridad de la información.
Características

    Interfaz Gráfica de Usuario (GUI): Utiliza JavaFX para ofrecer una interfaz atractiva y fácil de usar, permitiendo una interacción fluida.
    Gestión de Personas: Los usuarios pueden agregar nuevas personas a la lista mediante un formulario, que incluye validaciones para asegurar datos completos y válidos.
    Validación de Datos: La aplicación incluye un sistema de validación para verificar que los campos obligatorios no estén vacíos y que la edad sea un número válido.
    Alertas Informativas: Se proporcionan notificaciones claras para ayudar a los usuarios a resolver errores en la entrada de datos y confirmar acciones exitosas.

## Requisitos
### Para ejecutar esta aplicación, necesitarás:

    Java Development Kit (JDK) 11 o superior
    JavaFX SDK (asegúrate de tener configurado el path correctamente)
    Un IDE como IntelliJ IDEA, Eclipse o NetBeans para compilar y ejecutar el proyecto.

## Estructura del Proyecto

    src/: Carpeta que contiene el código fuente de la aplicación.
        eu/andreatt/ejerciciob_dein/application/: Contiene la clase principal HelloApplication.
        eu/andreatt/ejerciciob_dein/controller/: Contiene el controlador HelloController para la lógica de la interfaz gráfica.
        eu/andreatt/ejerciciob_dein/model/: Contiene la clase Persona, que define el modelo de datos.
    resources/: Carpeta que contiene los recursos de la aplicación.
        fxml/: Archivos FXML que definen la estructura de la interfaz gráfica.
        images/: Iconos e imágenes utilizados en la aplicación.

## Cómo Ejecutar la Aplicación

    Clona o descarga el repositorio a tu máquina local.
    Abre el proyecto en tu IDE y asegúrate de tener configurado el JDK y JavaFX correctamente.
    Ejecuta la clase HelloApplication para iniciar la aplicación.
    Interactúa con la interfaz para agregar personas a la lista.

## Uso de la Aplicación

    Agregar Persona: Completa los campos de nombre, apellido y edad, luego haz clic en "Agregar Persona".
    Validación de Entradas: Si se ingresan datos incorrectos o incompletos, se mostrará una alerta con el mensaje de error correspondiente.
    Confirmación de Éxito: Después de agregar una persona correctamente, se mostrará una notificación de éxito.
