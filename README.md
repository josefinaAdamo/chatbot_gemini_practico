Chatbot de Consola Impulsado por Google Gemini
Este proyecto presenta un chatbot de consola (CLI) robusto y flexible, desarrollado en Python y potenciado por el modelo Gemini de Google.

Su diseño se centra en la adaptabilidad, permitiendo que el asistente conversacional cambie de personalidad (Roles) bajo demanda.

✨ Características Principales
Flexibilidad de Roles: Permite configurar y alternar fácilmente entre diferentes personalidades para el chatbot, adaptando su estilo y conocimiento a la tarea.
Diseño Modular: La arquitectura está pensada para la facilidad de mantenimiento. Componentes clave como la memoria de conversación, la configuración de la API, y la gestión de Roles están separados.
🛠️ Instalación y Configuración
Sigue estos pasos para poner en marcha el chatbot:

1. Clave API de Gemini
Para autenticarte con el servicio de Google, necesitas tu clave de API:

Crea un archivo llamado .env en la carpeta raíz del proyecto.

Dentro de este archivo, pega tu clave de API en el siguiente formato:

GEMINI_API_KEY="TU_CLAVE_AQUI"
(Reemplaza "TU_CLAVE_AQUI" con tu clave real).

2. Instalación de Dependencias
Abre la terminal en la carpeta principal del proyecto e instala todas las dependencias requeridas usando pip:

pip install -r requirements.txt
