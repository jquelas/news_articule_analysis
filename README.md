# 📰 News Article Analysis

Este repositorio contiene un proyecto de análisis de texto con procesamiento de lenguaje natural (NLP) aplicado a una nota periodística de actualidad económica publicada en el diario La Nación. Utiliza herramientas como tokenización, lematización, eliminación de stopwords y análisis de sentimientos para extraer información útil del texto.

---

## 📄 Artículo Analizado

- **Título:** Plan económico: ¿cuál es el verdadero riesgo que preocupa a los empresarios?
- **Autor:** José Del Río  
- **Medio:** Diario La Nación  
- **Fecha de publicación:** 29 de junio de 2025  
- **URL:** [https://www.lanacion.com.ar/economia/plan-economico-cual-es-el-verdadero-riesgo-que-preocupa-a-los-empresarios-nid29062025/](https://www.lanacion.com.ar/economia/plan-economico-cual-es-el-verdadero-riesgo-que-preocupa-a-los-empresarios-nid29062025/)

En este artículo, el periodista José Del Río analiza la incertidumbre económica que afecta a empresarios argentinos en un contexto de reformas económicas, tipo de cambio y presión inflacionaria.

---

## ⚙️ Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/jquelas/news_articule_analysis.git
cd news_articule_analysis
```

2. Se recomienda el uso de un entorno virtual:
```bash
python -m venv venv
source venv/bin/activate  # en Windows usar venv\Scripts\activate
```

3. Instala las dependencias necesarias:
```bash
pip install -r requirements.txt
```

> Asegúrate también de tener instalado el modelo de idioma en español para spaCy:
```bash
python -m spacy download es_core_news_sm
```

---

## 📚 Bibliotecas utilizadas

Este proyecto emplea las siguientes bibliotecas de Python:

- `spaCy` – Tokenización, lematización y análisis gramatical (POS) del texto en español.
- `nltk` – Para la carga y uso de stopwords en español.
- `textblob` – Análisis básico de sentimientos (polaridad y subjetividad).
- `pysentimiento` – Análisis de sentimientos avanzado basado en modelos BERT, entrenado en español.
- `matplotlib` – Visualización gráfica de resultados.
- `seaborn` – Visualizaciones estadísticas mejoradas.
- `wordcloud` – Para la generación de nubes de palabras a partir del texto procesado.
- `pandas` – Manipulación y análisis de datos tabulares.
- `numpy` – Operaciones numéricas y estructuras de datos eficientes.

> ⚙️ Asegúrate de instalar estas dependencias en tu entorno virtual antes de ejecutar el proyecto.

---

## 📝 Licencia

Este proyecto está licenciado bajo la **GNU General Public License v3.0**. Consulta el archivo [LICENSE](./LICENSE) para más detalles.

---