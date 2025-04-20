
**Respuestas a las preguntas con explicaciones:**

1.  **Pregunta 1:**
    * Enunciado de la pregunta: El teorema de Nyquist proporciona una medida del ancho de banda de una señal:
    * Respuesta: b. Falso.
    * Explicación:
        * El teorema de Nyquist establece la frecuencia mínima a la que se debe muestrear una señal analógica para que pueda ser reconstruida con precisión. [cite: 203, 204]
        * Específicamente, la frecuencia de muestreo (fmuestreo) debe ser al menos el doble de la frecuencia más alta presente en la señal (ancho de banda f): fmuestreo ≥ 2f. [cite: 204, 269]
        * Por lo tanto, el teorema de Nyquist está relacionado con la frecuencia de muestreo, no con la medida del ancho de banda de la señal en sí.

2.  **Pregunta 2:**
    * Enunciado de la pregunta: El muestreo de señales permite:
    * Respuesta: d. Todas las anteriores.
    * Explicación:
        * El muestreo reduce la información a procesar al tomar "fotos" de la señal a intervalos discretos. [cite: 215, 218]
        * Estas "fotos" representan la señal continua en puntos específicos en el tiempo. [cite: 218]
        * Al reducir la cantidad de datos, se aceleran los procesamientos posteriores de la señal. [cite: 215, 225, 228]

3.  **Pregunta 3:**
    * Enunciado de la pregunta: Una señal constante, como pueda ser la de una pila de batería, no se puede muestrear:
    * Respuesta: a. Sí, todas las señales se pueden muestrear.
    * Explicación:
        * El muestreo es el proceso de tomar muestras de una señal a intervalos regulares. [cite: 218]
        * Aunque una señal constante no cambia con el tiempo, aún se puede muestrear tomando medidas de su valor en diferentes momentos. [cite: 258]
        * El resultado del muestreo de una señal constante sería una serie de valores iguales. [cite: 247, 248, 249, 250]

4.  **Pregunta 4:**
    * Enunciado de la pregunta: Ordene los elementos de un conversor analógico-discreto por orden de procesamiento:
    * Respuesta: a. Muestreo, cuantificación y codificador.
    * Explicación:
        * Un conversor analógico-digital (A/D) consta de tres partes principales: muestreador, cuantificador y codificador. [cite: 218, 219, 220]
        * El muestreador convierte la señal analógica en una señal discreta tomando muestras en el tiempo. [cite: 218]
        * El cuantificador asigna valores discretos a las muestras. [cite: 219]
        * El codificador convierte estos valores en un formato digital, como binario. [cite: 220]
        * Este es el orden en que se realiza el procesamiento. [cite: 221, 222, 223, 224]

5.  **Pregunta 5:**
    * Enunciado de la pregunta: El sobremuestreo consiste en:
    * Respuesta: a. Muestrear con una frecuencia más elevada que la de Nyquist.
    * Explicación:
        * El sobremuestreo implica muestrear una señal a una frecuencia mayor que la frecuencia de Nyquist. [cite: 276]
        * La frecuencia de Nyquist es la frecuencia mínima de muestreo requerida para capturar con precisión una señal. [cite: 203, 204]
        * Muestrear a una frecuencia más baja se llama submuestreo, y puede causar aliasing. [cite: 270, 271, 272, 273]

6.  **Pregunta 6:**
    * Enunciado de la pregunta: ¿Una señal que ha pasado a través de un conversor analógico-discreto puede volver a recuperarse completamente?
    * Respuesta: b. Sí, siempre que se haya respetado el teorema de Nyquist.
    * Explicación:
        * Una señal analógica puede reconstruirse a partir de sus muestras digitales si se cumple el teorema de Nyquist. [cite: 231, 232]
        * El teorema de Nyquist garantiza que no se pierda información esencial durante el muestreo. [cite: 203, 204]
        * Si la señal no se muestrea a la frecuencia de Nyquist, se produce una pérdida de información y la señal no se puede recuperar completamente. [cite: 205, 206]

7.  **Pregunta 7:**
    * Enunciado de la pregunta: La voz humana tiene un ancho de banda de 4 KHz, ¿a qué frecuencia debe de muestrearse toda señal de voz?
    * Respuesta: b. Según Nyquist a 8 KHz mínimo.
    * Explicación:
        * El teorema de Nyquist establece que la frecuencia de muestreo debe ser al menos el doble del ancho de banda de la señal. [cite: 203, 204, 269]
        * Si el ancho de banda de la voz humana es de 4 KHz, la frecuencia de muestreo mínima debe ser 2 \* 4 KHz = 8 KHz.

8.  **Pregunta 8:**
    * Enunciado de la pregunta: Sin el muestreo y la cuantificación no podrían hacerse filtros de señal:
    * Respuesta: b. Falso, las señales analógicas pueden filtrarse mediante filtros analógicos.
    * Explicación:
        * Las señales analógicas se pueden filtrar utilizando filtros analógicos. [cite: 226, 227]
        * El muestreo y la cuantificación permiten el filtrado digital, que ofrece ventajas como la flexibilidad y la facilidad de modificación. [cite: 226, 227]
        * Sin embargo, el filtrado analógico es un proceso separado y no depende del muestreo y la cuantificación.

9.  **Pregunta 9:**
    * Enunciado de la pregunta: Un alumno decide poner una cámara a las ruedas de su coche. La rueda gira a una frecuencia de cuatro vueltas por segundo, es decir, cada vuelta tarda 250 milisegundos, ¿a qué frecuencia gira?
    * Respuesta: b. Frecuencia = 4 Hz.
    * Explicación:
        * La frecuencia se mide en Hertz (Hz) y representa el número de ciclos por segundo.
        * Si la rueda gira cuatro vueltas por segundo, su frecuencia es de 4 Hz. [cite: 203]
        * La información sobre el tiempo que tarda cada vuelta (250 milisegundos) es un dato adicional pero no afecta la frecuencia en Hz.

10. **Pregunta 10:**
    * Enunciado de la pregunta: Si tuvieras que usar un algoritmo de compresión, ¿en qué momento del conversor A/D lo emplearías?
    * Respuesta: c. Después de la codificación, ya que la información sale binaria de dicho módulo y es fácilmente comprimible.
    * Explicación:
        * La compresión es más eficiente después de la codificación porque la información está en formato digital (binario). [cite: 228, 229]
        * Los algoritmos de compresión están diseñados para reducir la redundancia en los datos digitales. [cite: 228, 242]
        * Comprimir antes de la codificación podría ser menos eficiente ya que los datos aún no están en un formato optimizado para la compresión.

**Guía de Estudio del Tema 3: Captura y Digitalización de Señales**

**1.  Introducción a la Teoría de Muestreo y Cuantificación**

    * **Conceptos Clave:**
        * **Muestreo:** Proceso de tomar muestras de una señal continua a intervalos discretos de tiempo. [cite: 168, 169, 170]
        * **Cuantificación:** Proceso de convertir las muestras tomadas en valores numéricos discretos. [cite: 168, 169, 171]
        * **Discretización:** Proceso de convertir una señal continua en una señal discreta tanto en tiempo como en amplitud. [cite: 213, 214, 215, 216]
    * **Importancia:**
        * La teoría de muestreo y cuantificación es fundamental para la conversión de señales analógicas a digitales. [cite: 174, 175, 176, 177]
        * Permite representar señales del mundo real en un formato que las computadoras pueden procesar y almacenar.
    * **Ejemplo Ilustrativo:**
        * Mosaicos romanos: Utilización de un número limitado de colores y tamaños de teselas para representar una imagen compleja, ilustrando la discretización. [cite: 179, 180, 181, 182]

**2.  Sistemas de Conversión Analógico-Digital (A/D)**

    * **Señal Analógica:**
        * Señal continua que representa fenómenos físicos. [cite: 208, 209, 210, 211, 212]
        * Ejemplos: Sonido, luz, temperatura.
    * **Señal Digital (o Discreta):**
        * Señal que toma valores discretos. [cite: 213, 214, 215, 216]
        * Viene del muestreo y cuantificación de la señal analógica.
    * **Componentes de un Conversor A/D:**
        * **Muestreador:** Convierte la señal analógica a discreta tomando muestras a una frecuencia determinada. [cite: 218]
        * **Cuantificador:** Transforma las muestras en un conjunto limitado de valores discretos. [cite: 219, 220, 221, 222, 223, 224]
        * **Codificador:** Convierte los valores cuantificados en un formato digital (ej., binario). [cite: 219, 220, 221, 222, 223, 224]
    * **Ventajas de la Conversión A/D:**
        * Reducción de la complejidad de la señal. [cite: 225, 226, 227, 228, 229]
        * Facilita el filtrado de ruido. [cite: 225, 226, 227, 228, 229]
        * Permite el procesamiento digital, la compresión y el cifrado. [cite: 225, 226, 227, 228, 229]
        * Almacenamiento más eficiente y económico. [cite: 228, 229, 230, 231, 232, 233]

**3.  Muestreo**

    * **Proceso de Muestreo:**
        * Tomar muestras de una señal analógica a intervalos regulares. [cite: 258, 259, 260, 261, 262, 263, 264, 265, 266, 267]
        * Determinado por la señal de muestreo (tren de pulsos). [cite: 259, 260, 261, 262, 263, 264, 265, 266, 267]
    * **Teorema de Nyquist-Shannon:**
        * Establece la frecuencia mínima de muestreo (fmuestreo) necesaria para capturar con precisión una señal con un ancho de banda f: fmuestreo ≥ 2f. [cite: 203, 204, 268, 269]
    * **Consecuencias de un Muestreo Incorrecto:**
        * **Submuestreo (Undersampling):** La señal muestreada no representa fielmente la señal original, puede causar aliasing. [cite: 270, 271, 272, 273, 274, 275]
        * **Sobremuestreo (Oversampling):** Se capturan datos redundantes, lo que produce una reconstrucción errónea de la señal. [cite: 276, 277, 278, 279]

**4.  Cuantificación**

    * **Proceso de Cuantificación:**
        * Convertir las muestras tomadas en valores numéricos discretos. [cite: 279, 280, 281, 282, 283, 284, 285, 286]
        * La resolución depende del número de bits utilizados. [cite: 279, 280, 281, 282, 283, 284, 285, 286]
    * **Resolución y Calidad:**
        * Mayor número de bits = mayor resolución = mejor calidad de la señal digital. [cite: 289, 290, 291, 292, 293, 294, 295]
    * **Cuantificación Uniforme y No Uniforme:**
        * **Uniforme:** Intervalos de cuantificación iguales. [cite: 283, 284, 285, 286]
        * **No Uniforme:** Intervalos de cuantificación variables para mayor resolución en ciertas regiones. [cite: 283, 284, 285, 286]
    * **Cuantificación en la Captura de Imágenes:**
        * Las cámaras CCD cuantifican la luz en valores discretos por fotodiodo. [cite: 286, 287, 288]
        * La cuantificación determina la resolución o calidad de la imagen (ej., 256 niveles de gris). [cite: 289, 290, 291, 292, 293, 294, 295]
