# 📘 Proyecto Django - Guía Rápida de Instalación y Ejecución

Sigue estos pasos para instalar y ejecutar el proyecto en tu entorno local.

---

## 🚀 Requisitos

- Python 3.10 o superior
- Git
- Visual Studio Code (opcional)

---

## 1️⃣ Clonar el repositorio

Abre una terminal y ejecuta:

```bash
git clone https://github.com/usuario/nombre-del-repositorio.git
```

## 2️⃣ Abrir el proyecto en Visual Studio Code

- Abre Visual Studio Code como administrador.
- Ve a **Archivo > Abrir carpeta...** y selecciona la carpeta del proyecto.

## 3️⃣ Crear y activar entorno virtual

En la terminal integrada de VS Code:

```bash
python -m venv venv
.\venv\Scripts\activate
```

## 4️⃣ Instalar dependencias

```bash
pip install django
```

## 5️⃣ Verificar instalación

```bash
python --version (si no lo tienes lo descargas)
django-admin --version
```

## 6️⃣ Ejecutar el servidor

```bash
python manage.py runserver
```

Abre tu navegador y visita [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---