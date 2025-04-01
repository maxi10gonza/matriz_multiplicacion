# Multiplicación de Matrices - Proyecto Web

Este proyecto es una aplicación web que permite a los usuarios ingresar dos matrices y calcular su multiplicación utilizando un servidor Flask.

## 📁 Estructura de Archivos

```
matriz_multiplicacion/
│── app.py                # Servidor Flask (Backend)
│── static/
│   ├── script.js         # Lógica del cliente (Frontend)
│── templates/
│   ├── index.html        # Interfaz del usuario
```

## 🚀 Funcionamiento

### 1️⃣ Ingreso de dimensiones
- El usuario ingresa la cantidad de filas y columnas para las matrices.
- Se generan dinámicamente los campos de entrada para ingresar los valores.

### 2️⃣ Carga de datos
- Se presentan dos matrices vacías en la interfaz.
- El usuario llena los valores en los inputs correspondientes.

### 3️⃣ Envío de datos y multiplicación
- Se envían los datos al backend mediante una solicitud `POST`.
- El servidor Flask recibe las matrices y realiza la multiplicación mediante iteraciones.
- Si las dimensiones son inválidas, se muestra un mensaje de error.

### 4️⃣ Resultado en pantalla
- La matriz resultante se muestra en la interfaz web.

## 🔧 Instalación y Ejecución

1. Clonar el repositorio y entrar al directorio del proyecto.
2. Instalar Flask si no está instalado:
   ```sh
   pip install flask flask-cors
   ```
3. Ejecutar el servidor:
   ```sh
   python app.py
   ```
4. Abrir en el navegador:
   ```
   http://127.0.0.1:5000
   ```



