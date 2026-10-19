# Análisis de reseñas de Boohoo

Proyecto de Deep Learning del máster. Cogí reseñas de clientes de boohoo.com de un dataset de Hugging Face y quise ver qué opina la gente de la marca y en qué se diferencia de otras tiendas de moda online.

Primero limpié los textos (había bastantes caracteres raros, así que revisé cuáles aparecían antes de escribir la función de limpieza) y me quedé con las empresas del sector Shopping & Fashion. Después clasifiqué el sentimiento de cada reseña con un modelo de Transformers y saqué los temas principales con TF-IDF y NMF. Con eso pude ver qué temas generan más quejas y comparar a Boohoo con la media del sector.

El análisis está en `analisis_empresa - template.ipynb` y los resultados resumidos en la presentación `Analisis_de_reseñas_Boohoo.pptx`.

Para ejecutarlo:

```
pip install datasets pandas numpy scikit-learn transformers torch matplotlib seaborn jupyter
```
