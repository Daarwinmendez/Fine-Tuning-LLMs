# Fine-Tuning y Evaluación de Modelos Largos del Lenguaje

## Resumen del Proyecto
Este proyecto se centra en el fine-tuning y evaluación de modelos de NLP para tareas de Legal Summarization y Fake News Detection. Se realiza el entrenamiento de un modelo T5 para resumir documentos legales y de un modelo BERT para la clasificación de noticias (Fake News). El proyecto está implementado en Python y puede ejecutarse tanto en Jupyter Notebook (o Google Colab) como en forma de script.

## Objetivos
- Realizar fine-tuning de un modelo T5 en el dominio legal para generar resúmenes.
- Entrenar y evaluar un modelo BERT para detectar Fake News.
- Utilizar pipelines de Hugging Face y diversas métricas (ROUGE, Accuracy) para evaluar el desempeño.

## Arquitectura y Flujo de Trabajo
- **Preparación del Entorno:**  
  Instalación de todas las dependencias necesarias (ver [requirements.txt](requirements.txt)).
- **Legal Summarization:**  
  - Se utiliza un modelo T5 preentrenado que se fine-tunea en un dataset de documentos legales.
  - Se evalúa el desempeño del modelo a través de la métrica ROUGE.
- **Fake News Detection:**  
  - Se emplea un modelo BERT para clasificar noticias como "true" (real) o "fake".
  - Se mide la exactitud y se visualizan matrices de confusión para evaluar el desempeño.

## Instrucciones de Ejecución

### 1. Clonar el Repositorio
```bash
git clone https://github.com/Daarwinmendez/LLM-Applications.git
cd LLM-Applications
```

### 2. Instalar Dependencias
Instala las dependencias utilizando el archivo requirements.txt:
```bash
pip install -r requirements.txt
```

### 3. Ejecutar el Proyecto
* Jupyter Notebook / Google Colab:
Abre el archivo main_fine_tuning.ipynb y ejecuta las celdas de forma secuencial.
Script Python:

* Ejecuta el script con:
  ```bash
  python main_fine_tuning.py
  ```
(Verifica el nombre del script según corresponda.)

## Tecnologías Utilizadas

* Lenguaje: Python
* Entorno: Jupyter Notebook / Google Colab
* Librerías Principales:
  ```bash
  Transformers
  Datasets
  Evaluate
  Pandas, NumPy
  Matplotlib, Seaborn
  TensorFlow, Keras
  PyTorch
  Sentencepiece, Openpyxl, Scikit-Learn
  Resultados y Conclusiones
  ```
## Conclusiones
El proyecto demuestra el proceso de fine-tuning aplicado a tareas de NLP en dominios específicos (legal y Fake News). Se obtienen métricas de evaluación que permiten analizar la eficacia del modelo entrenado. La metodología puede servir como base para futuros experimentos o aplicaciones en procesamiento de lenguaje natural.
