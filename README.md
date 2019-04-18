# 20191.DL Fundamentos de Deep Learning
     
## Proyecto U3: Redes Convolucionales

Para el presente proyecto, solo debe ejecutar el _notebook_ asl_Alphabet.ipynb

A continuación se indican las tareas realizadas de acuerdo con lo pedido en el curso:

- Dataset: versión reducida de base de datos de lenguaje americano de señas, el cual se descarga de Dropbox al ejecutar el _notebook_.
- Tarea de aprendizaje y métrica de evaluación: clasificación de 29 gestos de la mano (A-Z, espacio, borrar, nada). Se evaluó mediante el cálculo de la exactitud. Se graficaron curvas de aprendizaje y matriz de confusión.
- Estrategia de resolución:  se evaluaron distintas arquitecturas de red con diferente dropout, se evaluó el efecto de la _batch normalization_, y se hizo _transfer learning_ utilizando AlexNet.
- Flujo de trabajo experimental:

        1. Evaluación de 4 arquitecturas
            1.1 Modelo A
            1.2 Modelo B
            1.3 Modelo C
            1.4 Modelo D
            1.5 Comparación de los modelos
            1.6 Matriz de confusión en validación y test
        2. _Transfer learning_ con AlexNet
        3. Efecto de la _batch normalization_
        4. Prueba de clasificación en video usando el mejor modelo

La prueba de clasificación en video y su resultado final, se puede seguir y observar al ejecutar el _notebook_ **DemoU3.ipynb**. En este caso se necesita la instalación de códecs de vídeo, lo cual se incluye en el _notebook_. El proceso puede tardar un poco debido al tamaño del video de prueba y al procesamiento de imágenes que hemos realizado, además del proceso de clasificación sobre cada imagen y la posterior creación del video final; por lo tanto, si solo se desea observar el resultado final este se encuentra dentro de la carpeta *mini_asl_alphabet.zip* con el nombre de _video2.mp4_.

### Integrantes

* CARVAJAL CASTAÑO HELBER ANDRÉS
* CASTRILLÓN OSORIO LUIS REINEL
* ROLDÁN VASCO SEBASTIÁN
