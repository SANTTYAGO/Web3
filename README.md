# Proyecto de Catálogo de Productos con ReactPy y Flask

Este proyecto es una aplicación web desarrollada con **ReactPy** y **Flask**, que muestra un catálogo de productos en formato de tarjetas. La aplicación utiliza componentes de **Material-UI (MUI)** para el diseño visual, como contenedores, cuadrículas y elementos de interfaz. Cada tarjeta presenta una imagen, el nombre del producto, una descripción, el precio y una calificación visualizada con un componente de clasificación.

## Tecnologías

- **Frontend**: ReactPy
- **Backend**: Flask
- **Diseño UI**: Material-UI (MUI)
- **Lenguaje**: Python
- **Módulos de Backend**: Flask, ReactPy
- **Sistema de gestión de UI**: Grid, Container, Paper, Typography, Rating

## Características

- Muestra una lista de productos en un formato amigable.
- Utiliza imágenes dinámicas basadas en IDs para simular contenido real.
- Cada producto tiene una calificación de 0 a 5 estrellas con precisión decimal.
- Interfaz moderna y responsiva utilizando Material-UI.

## Instalación

1. Clona este repositorio.
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecuta la aplicación:
   ```bash
   python main.py
   ```

## Datos

Los productos se cargan desde un archivo `datos.py`, que contiene un diccionario con la siguiente estructura:

```python
productos = [
    {
        "id": 1,
        "nombre": "Producto 1",
        "descripcion": "Descripción del producto 1",
        "precio": "$100",
        "rating": 4.5
    },
    ...
]
```
