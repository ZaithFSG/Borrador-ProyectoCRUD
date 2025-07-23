## 🚀 Pasos para Ejecutar el Proyecto desde Cero

1. **Cierra Visual Studio Code** si lo tienes abierto.

2. **Ábrelo como administrador**:
   - Haz clic derecho en el ícono de Visual Studio Code.
   - Selecciona **"Ejecutar como administrador"**.

3. **Abre una terminal** (`Ctrl + ñ`) y activa el entorno virtual con:

   ```powershell
   .\venv\Scripts\activate

Si ves (venv) al inicio de la línea en tu terminal, significa que el entorno está activado correctamente.

Instala Django (si aún no lo tienes):
pip install django

Verifica la instalación de Django:
django-admin --version

Deberías ver un número de versión como respuesta

Ejecuta el servidor de desarrollo:
python manage.py runserver

Abre tu navegador y visita:
http://127.0.0.1:8000/ (ejemplo)
