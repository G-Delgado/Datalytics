# Datalytics

## 📌 Justificación del Proyecto
Datalytics es una plataforma de análisis de datos con Machine Learning que permite a los usuarios cargar datasets, realizar análisis exploratorio y aplicar modelos de predicción. Su objetivo es facilitar la toma de decisiones basada en datos mediante herramientas interactivas y visuales.

## 📜 Historias de Usuario

### 1️⃣ Subida y Preprocesamiento de Datos
**Como usuario**, quiero subir datasets en formatos CSV, Excel y JSON para analizarlos en la plataforma.
**Criterios de aceptación:**
- Soporte para múltiples formatos de archivos.
- Verificación automática de la estructura de datos.
- Previsualización del dataset antes de cargarlo.

### 2️⃣ Visualización de Datos Interactiva
**Como analista de datos**, quiero visualizar mis datos mediante gráficos interactivos para detectar patrones.
**Criterios de aceptación:**
- Soporte para gráficos de barras, líneas, dispersión y boxplots.
- Filtros dinámicos para ajustar las visualizaciones.
- Descarga de gráficos en formatos PNG y SVG.

### 3️⃣ Aplicación de Modelos de Machine Learning
**Como científico de datos**, quiero entrenar modelos de Machine Learning en mis datasets.
**Criterios de aceptación:**
- Soporte para modelos de regresión, clasificación y clustering.
- Evaluación del rendimiento de los modelos con métricas clave.
- Exportación de modelos entrenados en formato pickle.

## 📌 Requerimientos Funcionales
✅ Autenticación de usuarios con JWT.
✅ Carga y preprocesamiento de datasets.
✅ Visualización interactiva de datos.
✅ Implementación de modelos de Machine Learning.
✅ API REST/GraphQL para la comunicación entre frontend y backend.
✅ Almacenamiento en bases de datos PostgreSQL y MongoDB.
✅ Despliegue en la nube con AWS/GCP usando Docker y Kubernetes.

## 🚫 Requerimientos No Funcionales
✅ Seguridad con autenticación y autorización.
✅ Escalabilidad para múltiples usuarios concurrentes.
✅ Optimización del rendimiento en procesamiento de datos.
✅ Soporte para despliegue en múltiples entornos.

## 🖥️ Pantallas de la Web App
1. **Inicio de Sesión / Registro** (Autenticación de usuarios).
2. **Dashboard Principal** (Panel con resumen de datos cargados y modelos entrenados).
3. **Carga de Datos** (Interfaz para subir y previsualizar datasets).
4. **Análisis Exploratorio** (Gráficos y visualización de estadísticas).
5. **Entrenamiento de Modelos** (Selección y configuración de modelos de ML).
6. **Resultados y Predicciones** (Despliegue de modelos y generación de predicciones).
7. **Historial de Análisis** (Lista de datasets y modelos usados previamente).

## 🎨 Diseño UI/UX
- **Colores principales:** Azul (#1E90FF), Blanco (#FFFFFF), Gris oscuro (#333333)
- **Tipografía:** Roboto / Open Sans
- **Diseño minimalista** con enfoque en la accesibilidad.

## 🏗️ Arquitectura del Sistema
### 📌 Frontend
- **Tecnologías:** React.js, Next.js, TailwindCSS
- **Estructura:** Componentes reutilizables y diseño modular

### 📌 Backend
- **Tecnologías:** Django/Flask, FastAPI
- **Base de datos:** PostgreSQL para datos estructurados, MongoDB/Redis para almacenamiento rápido
- **Autenticación:** JWT
- **API:** REST/GraphQL

### 📌 Infraestructura
- **Contenedores:** Docker
- **Orquestación:** Kubernetes
- **Cloud:** AWS/GCP
- **Monitorización:** Grafana, Kibana

## 📅 Roadmap de Desarrollo
1️⃣ **Semana 1-2:** Diseño UI/UX y arquitectura del sistema.
2️⃣ **Semana 3-4:** Desarrollo del backend con autenticación y carga de datos.
3️⃣ **Semana 5-6:** Implementación del frontend y visualización de datos.
4️⃣ **Semana 7-8:** Integración de modelos de ML y optimización.
5️⃣ **Semana 9:** Pruebas y despliegue en la nube.

## 📖 Contribución
¡Cualquier contribución es bienvenida! Si deseas colaborar, abre un issue o envía un PR.

## 📜 Licencia
Todavía ninguna :p

