# Repositorios con solución:
1. **Desarrollo de apis con logica del rag, tanto carga de datos, como consumir el modelo**
   
    [https://github.com/santiagorodriguez-dev/rag_01_apis](https://github.com/santiagorodriguez-dev/rag_01_apis)
   
2. **Frontal web para consumo de modelo**
   
    [https://github.com/santiagorodriguez-dev/rag_02_web](https://github.com/santiagorodriguez-dev/rag_02_web)

# Descripcion de prueba técnica
## Objetivo de la Prueba
Evaluar la capacidad del candidato para diseñar, implementar y optimizar un sistema RAG utilizando técnicas modernas de recuperación y generación de texto.

### Parte 1: Ingesta y Procesamiento de Datos
-  Obtención de datos:
Descarga un conjunto de documentos de una fuente abierta (puede ser un conjunto de artículos, documentación técnica o cualquier dataset textual).
Procesa los datos eliminando ruido y asegurando que sean utilizables en un sistema de búsqueda.
Base de datos vectorial:
Usa una base de datos vectorial (ej. FAISS, Elasticsearch, Weaviate o ChromaDB) para indexar los documentos con embeddings generados por un modelo de lenguaje (ej. OpenAI, Hugging Face, etc.).

### Parte 2: Recuperación de Información
-  Consulta y Recuperación:
Implementa un mecanismo para recuperar los documentos más relevantes según una consulta dada.

### Parte 3: Generación de Respuestas
-  Integración con LLM:
Implementa un modelo de lenguaje para generar respuestas utilizando los documentos recuperados como contexto.
Puedes usar modelos como GPT-4, Llama, Mistral o cualquier modelo open-source compatible.

### Parte 4: Creación de un frontend
-  Streamlit / Gradio / Chainlit:
Implementa un frontend para poder interactuar con el RAG.
