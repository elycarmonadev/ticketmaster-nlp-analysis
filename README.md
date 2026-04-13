# 🎟️ Proyecto Deep Learning - Ticketmaster NLP Analysis

Análisis de reseñas de Trustpilot de **Ticketmaster** (sector: Events & Entertainment) mediante técnicas de NLP y Deep Learning.

## 🎯 Objetivo

Analizar el sentimiento y los topics de las reseñas de Ticketmaster y compararlos con los de su competencia en el mismo sector.

## 📁 Estructura del proyecto

```
ticketmaster-nlp-analysis/
│
├── analisis_ticketmaster.ipynb        # Notebook principal
│
└── data/
    ├── trustpilot-reviews-123k.csv            # Dataset completo original
    ├── ticketmaster_reviews.csv               # Reseñas de Ticketmaster
    └── events_entertainment_reviews.csv       # Reseñas del Sector (sin Ticketmaster)
```

## 🔄 Flujo del análisis

1. Extracción y separación de datos
2. Limpieza de texto
3. Análisis de sentimiento (BERT)
4. Topic modeling (BERTopic)
5. Sentimiento por topic
6. Comparativa Ticketmaster vs competencia
7. Conclusiones

## 🛠️ Tecnologías

- Python 3.12
- pandas, numpy
- transformers (BERT)
- BERTopic
- scikit-learn
- matplotlib, seaborn, wordcloud
