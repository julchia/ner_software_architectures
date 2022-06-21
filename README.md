# NER Software Architectures

## <b>Español-Spanish</b>

<p align='justify'>Considerando que la mayor parte de la bibliografía disponible online (blogs, cursos, video-tutoriales, etc.) focalizan su atención en el desarrollo de modelos NLP en abstracto, se propone explorar diferentes arquitecturas de software que permitan desplegar, de manera escalable, modelos para reconocimientos de entidades, de sus siglas en inglés, NER (Named Entity Recognition).</p>

<p align='justify'>El punto de partida serán cuatro implementaciones NER diferentes dispuestas en entornos principalmente funcionales. Tras finalizar este ejercicio, quedarán disponibles bajo un único entorno híbrido funcional-orientado a objetos. Se intentará poner sobre la mesa los pro y contra de cada una de las implementaciones mencionadas pero sin ahondar al detalle respecto de sus particularidades, siendo que se dejará la correspondiente documentación según sea cada uno de los casos. El objetivo primero de este ejercicio es el despliegue de los modelos a nivel arquitectura de software.</p>

Como herramientas principales, el repositorio hace uso de [TensorFlow 2.0](https://www.tensorflow.org/) y [Hugging Face](https://huggingface.co/). En tanto que los modelos NER propuestos serán:

- Custom Random Fields
- biLSTM + Custom Random Fields
- ELMo
- BERT-based attention

El corpus de datos será el mismo para todos los ejemplos: https://www.kaggle.com/datasets/rohitr4307/ner-dataset

## TODO:

- Hacer TODO :D
