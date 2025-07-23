# 🎬 Netflix Auth App – Proyecto Fullstack (React + Django)

Este es un proyecto de autenticación de usuarios que simula el inicio de sesión estilo Netflix. Está dividido en frontend (React) y backend (Django), organizados en ramas separadas y una rama principal (`main`) que los unifica.

---

## 📁 Estructura del Repositorio
netflix-auth-app/
├── backend/ # Django – Backend API
├── frontend/ # React – Interfaz de usuario
├── manage.py
├── db.sqlite3
├── package.json # Frontend config
├── README.md

---

## 🧱 Requisitos Previos

- Python 3.10+
- Node.js 18+
- Git
- PowerShell (Windows) o Terminal (Linux/Mac)
- VSCode (recomendado)

---

## 🔁 Clonar el Repositorio

```bash
git clone https://github.com/Raul-Verdin/netflix-auth-app.git
cd netflix-auth-app

🌱 Trabajo con Ramas
Este proyecto está organizado en tres ramas principales:

Rama	    Descripción
backend	    Contiene solo el código Django
frontend	Contiene solo el código React
main	    Versión integrada de backend + frontend

---

🔄 Listar todas las ramas
git branch -a

📥 Crear y cambiar a la rama backend
git checkout origin/backend --track -b backend

📥 Crear y cambiar a la rama frontend
git checkout origin/frontend --track -b frontend

🔄 Cambiar de rama
git checkout main        # Ver todo el proyecto
git checkout backend     # Trabajar solo en backend
git checkout frontend    # Trabajar solo en frontend

✅ GUARDAR CAMBIOS en GitHub

1. 🧭 Asegúrate de estar en la raíz del proyecto

2. ✅ Verifica en que rama estas
git branch

3. 📦 Verifica los archivos modificados
git status

4. ➕ Agrega todos los cambios
git add .

5. 📝 Haz el commit
git commit -m "Que cambios hiciste"

6. 🚀 Sube tus cambios a GitHub
git push origin main

---

🐍 Configurar el entorno virtual (solo backend)
1. Crear el entorno virtual
python -m venv venv

2. Activar el entorno virtual
PowerShell (Windows):
    .\venv\Scripts\Activate.ps1

Si ves un error de permisos, ejecuta esto una sola vez:
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

3. Instalar dependencias
pip install -r requirements.txt

---

⚛️ Configurar el frontend (React)
Desde la carpeta frontend/:
cd frontend
npm install
npm start # o npm run dev dependiendo del script configurado

✅ Recomendaciones
Usa main cuando necesites que el backend y frontend trabajen juntos.
Usa backend o frontend para trabajar de forma aislada en cada parte del proyecto.
No muevas archivos de una rama a otra sin asegurarte de qué rama estás usando.
Haz pull regularmente si estás colaborando con otra persona.