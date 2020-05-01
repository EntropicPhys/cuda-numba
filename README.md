# CUDA con Python y Numba

Esta introducción a CUDA con Python mediante Numba está extraído en su casi totalidad del ["Numba tutorial for GTC 2017 conference"](https://github.com/ContinuumIO/gtc2017-numba). Se han actualizado algunos códigos, traducido al castellano, y adaptado un notebook para profundizar en implementación de map reduce. De esta forma, se muestra como un científico de datos y big data puede hacer uso de CUDA con Python para acelerar su código en GPU.

Este material es parte de la asignatura [*Arquitecturas y Paradigmas para Big Data*](https://masterds.es/?page_id=1949) del **Máster propio en Data Science y Big Data** de la Universidad de Sevilla.

La estructura es la siguiente:
1. Bases de Numba: Una introducción a Numba, un módulo de Python que permite compilar funciones.
2. Bases de CUDA: Una introducción a CUDA mediante Numba, mediante la compilación de ufunc de Numpy.
3. Gestión de Memoria: Introducción al manejo de arrays en GPUs, minimizando la transferencia de datos desde y hacia la GPU.
4. Map-Reduce en CUDA: Una demostración de cómo paralelizar las operaciones map y reduce en la GPU.
5. Kernels de CUDA (pendiente): Una muestra de cómo implementar una función kernel en CUDA, haciendo uso explícito de los hilos.
6. Depuración (pendiente): Algunas herramientas para depurar código CUDA, y típicos errores cometidos.
7. Extra (pendiente): Generación de números aleatorios en la GPU, uso de memoria on-chip (shared) y definición de gufunc.
