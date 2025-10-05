![](./images/nlp_banner.png)



## Especialización en Inteligencia Artificial 
## Materia de Procesamiento del Lenguaje Natural


### Alumno: Martin Brocca

### Contenido: 


[desafío 1](./desafios/desafio_1/Desafio_1.ipynb) :
    - Explorar cómo representar y analizar texto, primero, vectorizar documentos y medir su similaridad para ver si coincide con el sentido del contenido y las etiquetas. Luego, armar un clasificador por prototipos comparando documentos de test con los de entrenamiento. Después, entrenar modelos de Naïve Bayes (Multinomial y ComplementNB) ajustando parámetros para mejorar el f1-score. Finalmente, trabajar con la matriz término-documento para estudiar la similaridad entre palabras y reflexionar sobre su interpretación.
  
[desafío 2](./desafios/desafio_2/Desafio_2.ipynb) :
    - Generación y ensayo de embeddings creados con la librería Gensim a partir de los modelos CBOW y Skipgram. Los embeddings se generaron a partir de un corpus en inglés basado en las novelas de Harry Potter. Para visualizar agrupación entre vectores se utilizó TSNE con librería Sklearn.
  
[desafío 3](./desafios/desafio_3/Desafio_2.ipynb) :
    - Modelo de lenguaje con tokenizacion por caracteres: Implementacion y comparacion de tres arquitecturas de redes neuronales recurrentes (SimpleRNN, LSTM y GRU) para la generación de texto a nivel de caracteres utilizando el corpus de las novelas de Harry Potter.

### Estructura del repositorio:
```bash
.
├── desafios
│   ├── desafio_1
│   │   └── Desafio_1.ipynb
│   └── desafio_2
│   │   └── Desafio_2.ipynb
│   |   ├── images
│   |   │   ├── Embeddings2d.png
│   |   │   └── Embeddings3d.png
|   └── desafio_3
│   │   └── Desafio_3.ipynb
│       ├── best_GRU.pt
│       ├── best_LSTM.pt
│       ├── best_model.pt
|       ├── best_SimpleRNN.pt
|
├── images
│   └── nlp.png
└── README.md
