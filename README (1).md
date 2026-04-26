# Sistema de Inventario para Tiendas Pequeñas

Aplicación web desarrollada con Python y Django para que dueños de tiendas pequeñas puedan gestionar su inventario de manera sencilla, sin necesidad de conocimientos técnicos.

---

## ¿Qué hace este proyecto?

La idea es simple: muchas tiendas de barrio llevan el inventario a mano o en un cuaderno, y eso genera errores, productos agotados sin darse cuenta y pérdidas innecesarias. Esta app resuelve eso.

Con el sistema podés:

- Registrar productos con nombre, categoría, precio y cantidad
- Ver el stock actual de todos tus productos en un solo lugar
- Recibir alertas cuando un producto está por agotarse
- Consultar el historial de entradas y salidas de mercancía
- Buscar productos por nombre o categoría
- Acceder con usuario y contraseña 

---

## Tecnologías usadas

- Python 
- Django 
- SQLite 
- HTML5 / CSS3
- Bootstrap 5

---

## Cómo correr el proyecto

### 1. Clonar el repositorio

```bash
git clone https://github.com/jcarrasc7/Sistema-de-inventario-para-tiendas-peque-as.git
cd Sistema-de-inventario-para-tiendas-peque-as
```

### 2. Crear entorno virtual e instalar dependencias

```bash
python -m venv env
source env/bin/activate      
pip install -r requirements.txt
```

### 3. Aplicar migraciones

```bash
python manage.py migrate
```

### 4. Crear superusuario (administrador)

```bash
python manage.py createsuperuser
```

### 5. Correr el servidor

```bash
python manage.py runserver
```

Abrí el navegador en `http://127.0.0.1:8000` y listo.

---

## Estructura del proyecto

```
sistema-inventario/
│
├── inventario/          # App principal
│   ├── models.py        # Modelos de base de datos
│   ├── views.py         # Lógica de las vistas
│   ├── urls.py          # Rutas de la app
│   └── templates/       # Plantillas HTML
│
├── static/              # Archivos estáticos (CSS, JS)
├── manage.py
├── requirements.txt
└── README.md
```




