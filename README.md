![](./images/nlp_banner.png)



## Especialización en Inteligencia Artificial 
## Materia de Procesamiento del Lenguaje Natural


### Alumno: Martin Brocca

### Contenido: 


[desafío 1](./desafios/desafio_1/Desafio_1.ipynb) :
    - Explorar cómo representar y analizar texto, primero, vectorizar documentos y medir su similaridad para ver si coincide con el sentido del contenido y las etiquetas. Luego, armar un clasificador por prototipos comparando documentos de test con los de entrenamiento. Después, entrenar modelos de Naïve Bayes (Multinomial y ComplementNB) ajustando parámetros para mejorar el f1-score. Finalmente, trabajar con la matriz término-documento para estudiar la similaridad entre palabras y reflexionar sobre su interpretación.
  
[desafío 2](./desafios/Desafio_2.ipynb) :
    - Generación y ensayo de embeddings creados con la librería Gensim a partir de los modelos CBOW y Skipgram. Los embeddings se generaron a partir de un corpus en inglés basado en las novelas de Harry Potter. Para visualizar agrupación entre vectores se utilizó TSNE con librería Sklearn.
  

### Estructura del repositorio:
```bash
.
├── desafios
│   ├── desafio_1
│   │   └── Desafio_1.ipynb
│   └── desafio_2
│   │   └── Desafio_2.ipynb
│       ├── images
│       │   ├── Embeddings2d.png
│       │   └── Embeddings3d.png
├── images
│   └── nlp.png
└── README.md
