## Sentiment Analysis con un dataset de comentarios de productos etiquetados con los sentimientos "reales".
Al encontrarse los comentarios etiquetados, se pueden implementar varios modelos y evaluar la performance.
* Primero se hizo un análisis con el método VADER (rule-based) y se calcularon las métricas de performance.
* Luego se cargó el modelo de embeddings Glove y se pasaron los comentarios a vectores numéricos normalizados.
* Se implementaron algunos modelos de Machine Learning (Regresión Logística, SVC y Random Forest) y se calcularon las métricas.
* Finalmente, se hizo un modelo que incluye los resultados del método VADER como nueva feature, y se implementó un modelo SVC.
