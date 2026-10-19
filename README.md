# Análisis de reseñas con NLP — Boohoo

Análisis de reseñas de clientes de **boohoo.com** para medir su sentimiento, descubrir de qué se quejan o qué valoran y compararlo con otras empresas del sector *Shopping & Fashion*.

## Qué incluye

1. **Extracción y limpieza**: carga del dataset desde Hugging Face, análisis de caracteres y función de limpieza de texto.
2. **Sentimiento**: clasificación de cada reseña con un modelo de **Transformers**.
3. **Topics**: extracción de temas con **TF-IDF + NMF**.
4. **Sentimiento por topic**: qué temas generan opiniones positivas o negativas.
5. **Comparativa con el sector**: Boohoo frente a la media de otras empresas.
6. **Visualizaciones y conclusiones** para negocio.

## Archivos

| Archivo | Descripción |
|---|---|
| `analisis_empresa - template.ipynb` | Notebook con todo el análisis |
| `Analisis_de_reseñas_Boohoo.pptx` | Presentación de resultados |
| `emp_100_reviews.xlsx` | Muestra de reseñas |

## Tecnologías

Python · Hugging Face (`datasets`, `transformers`) · Pandas · scikit-learn (TF-IDF, NMF) · Matplotlib · Seaborn

## Cómo ejecutarlo

```bash
pip install datasets pandas numpy scikit-learn transformers torch matplotlib seaborn jupyter
jupyter notebook "analisis_empresa - template.ipynb"
```

---
Proyecto del Máster en Data Science & IA (Evolve) · [Daniel Alconada](https://github.com/danialco9)
