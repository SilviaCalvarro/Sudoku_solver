# Sudoku_solver

Proyecto que tiene como finalidad poner en práctica conocimiento de procesamiento de imágenes, redes neuronales convolucionales y metodologías Backtracking. El proyecto consiste en 3 bloques:

1. Un primero donde realizo una serie de operaciones dentro del campo del procesamiento de imágenes para exprimir la mayor cantidad de información de interés posible de la fotografía. Para ello he utilizado la librería OpenCV y he diferenciado cada una de las celdas del sudoku e identificado si poseían o no un valor numérico en su interior. Las visualizaciones de este apartado están hechas con la librería matplotlib.
2. Un segundo bloque donde entreno una red neuronal convolucional (CNN) con el dataset MNIST para poder predecir los números iniciales del sudoku extraídos del apartado anterior. He utilizado el framework keras y la librería de visualización visualkeras.
3. Por último, me he informado de la metodología de resolución de problemas denominada Backtracking y he implementado el algoritmo que resuelve el sudoku en sí. Esta técnica consiste en «ir probando» combinaciones de valores y solo eliminar valores añadidos si se comprueba que están mal colocados. Las visualizaciones de este último apartado se realizaron con la librería seaborn.

He realizado una [presentación en Genially](https://view.genial.ly/620612faf06c4000110145a2/presentation-resolvedor-de-sudoku) para hacer más visuales los resultados.

Mejoras futuras:

1. Generalizar el procesamiento de imágenes: que no tenga que estar centrada y recta la imagen de entrada con el sudoku.
2. Utilizar un dataset para la CNN que no sea el MNIST. Es la parte más sensible del proyecto.
