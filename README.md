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

- `NumPy` - Para operaciones numéricas y estructuras de datos eficientes.
- `Pandas` - Para manipulación y análisis de datos tabulares.
- `Matplotlib` - Para visualización gráfica de los resultados.
- `Seaborn` - Para visualizaciones estadísticas mejoradas.
- `spaCy` – Tokenización y lematización en español
- `nltk` – Stopwords en español
- `textblob` – Análisis de sentimientos
- `matplotlib` – Visualización de resultados
- `vaderSentiment` (opcional) – Análisis de polaridad para textos traducidos

---

## 📝 Licencia

Este proyecto está licenciado bajo la **GNU General Public License v3.0**. Consulta el archivo [LICENSE](./LICENSE) para más detalles.

---