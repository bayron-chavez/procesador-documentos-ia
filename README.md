# 📄 Procesador Multimodal de Documentos con IA

Este proyecto es un asistente inteligente y autónomo diseñado en **Python** que automatiza la auditoría y extracción de datos desde documentos complejos (PDF, TXT, Word). Utiliza arquitecturas avanzadas de IA mediante las APIs de **Google Gemini 2.5 Flash** y **OpenAI (GPT-4o-mini)** para transformar información desestructurada en JSONs perfectamente formateados y listos para producción.

### 🚀 Características Clave
- **Extracción Multimodal Nativa:** Gemini procesa PDFs directamente mediante visión analítica, interpretando tablas y gráficos sin romper el formato.
- **Salida Estructurada (Structured Outputs):** Integración estricta con **Pydantic** para garantizar que las respuestas de la IA respeten el modelo de datos del negocio.
- **Arquitectura Multimotor:** Interfaz dinámica en **Streamlit** que permite al usuario alternar en tiempo real entre los motores de Google y OpenAI.

### 🛠️ Tecnologías Utilizadas
- Python 3.10+
- Streamlit (Interfaz de usuario)
- Google GenAI SDK & OpenAI SDK
- Pydantic (Validación y tipado de datos)

### 📦 Instalación y Uso

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/tu-repositorio.git](https://github.com/tu-usuario/tu-repositorio.git)