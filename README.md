# Algoritmo de Haar:

El algoritmo de Haar es un método utilizado en visión por computadora y reconocimiento de patrones para detectar objetos en imágenes. Este algoritmo se basa en la detección de características específicas de los objetos, como bordes, esquinas y cambios bruscos de intensidad de píxeles, a través de la aplicación de filtros convolucionales.

El proceso de detección comienza con la selección de una ventana deslizante de tamaño fijo que se mueve por toda la imagen de entrada. Para cada posición de la ventana, se calcula una serie de características Haar que se utilizan para determinar si la ventana contiene o no el objeto de interés. Estas características se calculan a partir de la diferencia de sumas de píxeles de regiones adyacentes de la imagen.

Una vez que se han calculado todas las características para una ventana, se utiliza un clasificador para determinar si la ventana contiene el objeto de interés o no. El clasificador se entrena previamente utilizando un conjunto de imágenes positivas y negativas que representan el objeto y el fondo, respectivamente.

El algoritmo de Haar es utilizado en una variedad de aplicaciones de visión por computadora, incluyendo el reconocimiento facial, la detección de objetos en tiempo real y la segmentación de imágenes. Aunque es una técnica relativamente antigua, sigue siendo una herramienta útil y efectiva para la detección de objetos en imágenes.

# Tipos de algoritmos y usos:


1. Haar cascades: son una colección de características Haar que se utilizan para la detección de objetos en tiempo real. Las Haar cascades se utilizan ampliamente en aplicaciones de reconocimiento facial, detección de objetos y seguimiento de objetos.
2. Haar-like features: son características Haar que se utilizan para la detección de rostros y objetos en imágenes fijas. Estas características se utilizan en el algoritmo de Haar para determinar si una ventana contiene un objeto de interés.
3. Harr wavelets: son un tipo de transformada wavelet que se utiliza en el procesamiento de señales. La transformada wavelet de Haar es una transformada discreta que se utiliza para descomponer una señal en diferentes niveles de resolución.
4. Harr-Like Transform (HLT): es una técnica que se utiliza en la compresión de imágenes para reducir el tamaño de una imagen sin perder demasiada información. La técnica utiliza características similares a las características Haar para dividir la imagen en diferentes bloques y comprimirlos por separado.
5. Boosting-based classifiers: son clasificadores que utilizan una combinación de características Haar y otros tipos de características para mejorar la precisión de la detección de objetos. Estos clasificadores se utilizan en aplicaciones como la detección de objetos en tiempo real y el reconocimiento facial.

En resumen, los diferentes tipos de características Haar se utilizan en diversas aplicaciones de visión por computadora y procesamiento de señales para la detección de objetos, la compresión de imágenes y la mejora de la precisión de los clasificadores.
