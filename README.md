# Sistema de Registro de Visitantes

## Descripción

Este proyecto consiste en una aplicación de escritorio desarrollada en Python que permite registrar y gestionar visitantes mediante una interfaz gráfica.
El sistema permite agregar, actualizar, eliminar y visualizar registros de visitantes utilizando un formulario y una tabla.

La aplicación fue desarrollada aplicando principios de **Programación Orientada a Objetos (POO)** y una estructura organizada en módulos para separar los modelos, servicios y la interfaz gráfica.

## Funcionalidades

* Registrar visitantes.
* Editar información de visitantes existentes.
* Eliminar visitantes del registro.
* Visualizar los visitantes en una tabla.
* Limpiar los campos del formulario.

## Tecnologías utilizadas

* Python 3
* Tkinter (biblioteca estándar para interfaces gráficas)

No se utilizaron librerías externas.

## Estructura del proyecto

El proyecto está organizado de la siguiente manera:

* **modelos:** contiene la clase que representa al visitante.
* **servicios:** maneja la lógica del sistema y la gestión de datos.
* **ui:** contiene la interfaz gráfica desarrollada con Tkinter.
* **main.py:** archivo principal que inicia la aplicación.

## Ejecución del programa

1. Descargar o clonar el repositorio.
2. Ejecutar el archivo principal:

```
python main.py
```

Se abrirá la ventana del sistema de registro de visitantes.

## Características técnicas implementadas

* Programación Orientada a Objetos (POO).
* Encapsulamiento en la gestión de datos.
* Inyección de dependencias entre la interfaz y el servicio.
* Uso de la biblioteca estándar **Tkinter** para la interfaz gráfica.

## Nota

Se generó un archivo ejecutable utilizando PyInstaller para probar la aplicación.  
Por esta razón, en el repositorio también se incluyen las carpetas `build`, `dist` y el archivo `.spec`, los cuales son generados automáticamente durante ese proceso.
