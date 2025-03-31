# Aplicación de Tareas con Django y React

## Descripción

Esta es una aplicación web de tareas creada con Django/Django Rest y React.

## Capturas de Pantalla

A continuación, se muestran algunas capturas de pantalla de la aplicación en funcionamiento:

### Crear Tarea

![Principal](</imgs/Principal(2).png>)

Descripción: Interfaz para añadir una nueva tarea.

### Editar Tarea

![Editar Tarea](/imgs/ModoEditar.png)

Descripción: Interfaz para modificar o eliminar la información de una tarea existente.

### Vista de Rest Framework

![Vista del back y sus Tareas](/imgs/Rest.png)

Descripción: Muestra la API y los datos en formato JSON con de Rest.

## Requisitos Previos

- Python 3.8 o superior
- Node.js 16 o superior
- npm instalado

## Instalación y Configuración

### 1. Clonar el Repositorio

```bash
git clone <URL_DEL_REPOSITORIO>
cd <NOMBRE_DEL_REPOSITORIO>
```

### 2. Crear Entorno Virtual

Instalar `virtualenv` si no lo tienes:

```bash
pip install virtualenv
```

Crear un entorno virtual:

```bash
python -m venv venv
```

Activar el entorno virtual:

- En sistemas Unix/Linux/Mac:

```bash
source venv/bin/activate
```

- En sistemas Windows:

```bash
venv\Scripts\activate
```

### 3. Instalar Dependencias y levantar el servidor Back

Instalar las dependencias del proyecto especificadas en `requirements.txt` y levantar el servidor:

```bash
pip install -r requirements.txt
python manage.py runserver
```

### 4. Levantar la Aplicación Frontend

Abrir una terminal y configurar el cliente:

```bash
cd client
npm i -D @vitejs/plugin-react-swc
npm run dev
```

La aplicación estará disponible en `http://localhost:8000/tasks/api/v1/tasks/` para el backend y en el puerto `http://localhost:5173/tasks/` de desarrollo de Vite para el frontend.

---
