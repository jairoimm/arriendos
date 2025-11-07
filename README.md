# 🏠 Proyecto Arriendos — Plataforma de Gestión de Propiedades

**Arriendos** es una aplicación web desarrollada con **Django** que permite gestionar propiedades disponibles para arriendo.  
El sistema está diseñado para facilitar la administración de inmuebles, usuarios y procesos relacionados con alquileres, ofreciendo una base sólida para escalar y agregar nuevas funcionalidades.

---

## 🚀 Tecnologías principales

- **Python 3**
- **Django 5.1**
- **PostgreSQL**
- **python-dotenv** para manejo de variables de entorno
- **psycopg2** como conector de base de datos

---

## ⚙️ Funcionalidades implementadas o previstas

- Panel de administración para gestionar propiedades, arrendatarios y contratos  
- Sistema de autenticación de usuarios  
- Configuración mediante variables de entorno (`.env`)  
- Integración con base de datos PostgreSQL  
- Estructura modular y escalable  
- Código limpio y mantenible siguiendo buenas prácticas de Django  

---

## 🛠️ Instalación y configuración

2 Crear entorno virtual

python -m venv venv
# Activar el entorno virtual
# En Windows:
venv\Scripts\activate
# En macOS / Linux:
source venv/bin/activate

3 instalar dependencias
pip install -r requirements.txt

4 Configurar variables de entorno
DB_USER=postgres
DB_PASSWORD=tu_contraseña

5 Ejecutar migraciones e iniciar el servidor
python manage.py migrate
python manage.py runserver

Estructura del proyecto

arriendos/
│
├── manage.py
├── requirements.txt
├── .env
├── .gitignore
├── arriendos/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── ...
└── apps/
    ├── propiedades/
    ├── usuarios/
    └── ...


Autor
Desarrollado por Jairo Muñoz
💼 Proyecto personal para portafolio y práctica profesional de desarrollo con Django.

Licencia
Este proyecto se distribuye bajo la licencia MIT.
Puedes usarlo, modificarlo y distribuirlo libremente.
