# Pearl Store

Aplicación web académica para una tienda de joyería especializada en **perlas**, desarrollada con **Python, Flask, MySQL, HTML y CSS**.

El proyecto integra un frontend para la visualización de productos con un backend estructurado mediante servicios y rutas, conectado a una base de datos para gestionar clientes, productos, compras, devoluciones, sucursales y comentarios.

## Tecnologías

* Python
* Flask
* MySQL
* HTML5
* CSS3
* JavaScript
* MySQL Connector

## Características

* Catálogo de joyería y productos.
* Gestión de clientes.
* Gestión de productos.
* Registro de compras.
* Gestión de devoluciones.
* Gestión de sucursales.
* Sistema de comentarios.
* API organizada mediante rutas y servicios.
* Persistencia de información en MySQL.
* Interfaz web para la tienda de perlas.

## Arquitectura

El backend utiliza una organización por **rutas y servicios**, separando la lógica de las diferentes funcionalidades de la aplicación:

```text
Pearl Store/
├── routes/
│   ├── cliente_routes.py
│   ├── compra_routes.py
│   ├── producto_routes.py
│   ├── devolucion_routes.py
│   ├── sucursal_routes.py
│   └── Comentarios_routes.py
│
├── cliente_service.py
├── compra_service.py
├── producto_service.py
├── devolucion_service.py
├── comentarios.py
├── app.py
├── config.py
│
└── PAGINA NATU/
    ├── index.html
    ├── css/
    └── img/
```

## Contexto

**Proyecto académico universitario** orientado al desarrollo de aplicaciones web, integración de backend con bases de datos y gestión de información mediante una arquitectura organizada por rutas y servicios.

## Estado

**Proyecto académico / de aprendizaje.**

## Autora

**Sara Otero**

Ingeniería de Software.
