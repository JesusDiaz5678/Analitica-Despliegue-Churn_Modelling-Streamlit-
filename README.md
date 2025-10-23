# Analítica – Despliegue Churn Modelling con Streamlit

Este proyecto implementa un sistema de predicción de abandono de clientes (Churn) utilizando el modelo de arbol de decisión. La aplicación está desarrollada en Python e implementada mediante Streamlit para visualización web.

---
## Aplicación desplegada

Puedes acceder al despliegue público en el siguiente enlace:

https://practica4desplieguechurnw.streamlit.app/

---

## Archivos principales del proyecto

Cada uno de los archivos necesarios se localizan en el siguiente enlace: https://github.com/JesusDiaz5678/Analitica-Despliegue-Churn_Modelling-Streamlit-.git

- `app.py` → Código principal de la aplicación alojado en el archivo 4.Despliegue_Grafico_Churn_Modelling.ipynb. Descague el código y modifique el nombre por app.py
- `requirements.txt` → Lista de dependencias necesarias
- `modelo.pkl` / modelos entrenados → arbol de decisión
- `README.md` → Documentación del proyecto


## Despliegue GitHub – Streamlit

### 1️⃣ Crear una cuenta en GitHub

1. Ve a: https://github.com
2. Haz clic en **Sign up**
3. Completa el registro:
   - Usuario
   - Correo electrónico
   - Contraseña
4. Confirma tu cuenta

---

### 2️⃣ Crear un nuevo repositorio

1. Inicia sesión en GitHub
2. Haz clic en el botón **+** (esquina superior derecha) → **New repository**
3. Asigna un nombre al repositorio (ejemplo: `mi-app-streamlit`)
4. Marca la casilla **Add a README file**
5. Haz clic en **Create repository**

---

### 3️⃣ Subir tu proyecto al repositorio

1. Dentro del repositorio, haz clic en:
   - **Add file** → **Upload files**
2. Arrastra los archivos principales del proyecto:
   - `app.py`
   - `requirements.txt`
   - `modelo.pkl` (u otros modelos)
3. (Opcional) Puedes incluir notebooks usados para la creación de los modelos
   - **⚠️ Nota:** evita subir datos confidenciales
4. Haz clic en **Commit changes** para guardar

---

### 4️⃣ Conectar el proyecto con Streamlit Community Cloud

1. Ve a: https://streamlit.io/cloud
2. Inicia sesión con tu cuenta de GitHub:
   - **Free / Login with GitHub**
3. Haz clic en **Create app** / **Deploy a public app from GitHub**
4. Selecciona:
   - El repositorio (ej: `tuusuario/mi-app-streamlit`)
   - La rama (**main**, por defecto)
   - El archivo principal (**app.py**)
5. Haz clic en **Deploy**

---

Streamlit instalará automáticamente las dependencias y publicará la aplicación.


