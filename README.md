#  Proyecto Final: API de Análisis de Sentimientos con IA

Este repositorio contiene la implementación de un sistema *end-to-end* de Inteligencia Artificial capaz de clasificar reseñas de texto (películas) como **Positivas** o **Negativas**.

##  Descripción del Proyecto
El objetivo es demostrar el flujo de trabajo completo de MLOps Básico:
1.  **Entrenamiento:** Se entrenó una Red Neuronal Profunda utilizando **TensorFlow/Keras** y el dataset IMDB (25,000 reseñas).
2.  **Backend:** Se desarrolló una API RESTful con **Flask** para servir el modelo.
3.  **Despliegue:** Se implementó un despliegue en la nube utilizando **Google Colab** y **ngrok** para exponer el servicio a internet.

##  Tecnologías Utilizadas
* **Lenguaje:** Python 3.9+
* **IA/ML:** TensorFlow, Keras, NumPy.
* **Web/API:** Flask, Flask-CORS.
* **Infraestructura:** Google Colab, Pyngrok (Túnel HTTP).

##  Instrucciones de Ejecución
Este proyecto está optimizado para correr en la nube sin instalaciones locales.

1.  Abrir el archivo notebook (`.ipynb`) en **Google Colab**.
2.  **Fase 1:** Ejecutar la celda de entrenamiento para generar el archivo `modelo_sentimientos.h5`.
3.  **Fase 2:** Insertar tu *Authtoken* personal de [ngrok](https://dashboard.ngrok.com) y ejecutar la celda para levantar el servidor.
4.  **Prueba:** Utilizar la URL pública generada (ej. `https://xyz.ngrok-free.app/predict`) para enviar peticiones POST con el JSON de prueba.

##  Autor
**José Antonio Peña Reyes, MASI**
*Profesor Universitario*
