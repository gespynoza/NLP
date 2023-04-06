# Natural Language Processing (NLP)

En este notebook se mostrará cómo utilizar el modelo GPT-2 junto con TensorFlow para generar texto a partir de keywords, que en este caso serán "inteligencia" y "artificial"

El notebook se divide en los siguientes apartados:

Procesamiento de la noticia: se el extracto de una noticia sobre IA.
Tokenización: se utiliza la clase GPT2Tokenizer de Transformers para tokenizar el texto.
Embedding: se utiliza la clase TFGPT2Model de Transformers para obtener los embeddings de las palabras del texto.
Entrenamiento: se entrena un modelo de TensorFlow para predecir las palabras siguientes dado un conjunto de palabras previas y las keywords.
Generación de texto: se utiliza el modelo entrenado para generar texto a partir de las keywords.

