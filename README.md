![header](doc/LogoHeader.png)
#### Author
FS <br>
2023

En este repositorio se encontrarán los diferentes temas abordados en la materia **Natural Language Procesing**. Los temas vinculados a la materia se muestran en este repositorio junto con la resolución de los ejercicios propuestos en las diferentes etapas de la cursada. :

### 1. Preprocesamiento de texto
Las diferentes herramientas de preprocesamiento de texto se mencionan a continuación.

#### 1.1 Vectorización de texto
Es una metodología en Procesamiento Natural de Lenguaje que permite mapear palabras o frases de un vocabulario a un vector correspondiente de números reales,  el cuál es el formato que los modelos de **Machine Learning** soportan.
##### Técnicas de vectorización de texto
Dentro de las técnicas más comunes de vectorización de texto podemos considerar las siguientes:
1. Vectores de frecuencia: por cada palabra en el **corpus** se calcula un vector que representa cuántas veces cada palabra del vocabulario aparece en ese documento.
2. **One-hot encoding**: por cada documento en el corpus se calcula un vector que representa la aparación de cada palabra del vocabulario en el documento.
3. **Term frequency - Inverse term frequency**

#### 1.2 Tokenización
Es un proceso en el cual una sentencia o documento es dividida en palabras o términos individuales. Los símbolos son dejados aparte para luego tratarlos (ver figura 1)
<p align = "center">
<img alt = "imagen1" src = imgs\tokenization.png style="width:400px; height:auto" style= "display: block; margin: 0 auto">
</p>
<p align = "center"> Figura 1.  Ejemplo de tokenización [1]. </p>

#### 1.3 **Steaming**
Devolverá el tallo de una palabra, que no necesita ser idéntica a la raíz morfológica de la palabra.

#### 1.4 Lematización 
Devolverá la raíz de una palabra.

#### 1.5 Part of speech (POS) tagging
Es el proceso de clasificar cada término en un texto en sus categorías gramaticales, etiquetándolos  por ejemplo como sustantivo (noun), verbo (verb), adjetivo (adj), etc.

#### 1.6 Name-entity recongnition (NER)
Proceso de clasificar nombres de entidades en categorías predefinidas a las cuales pertenecen.


### 2. Embeddings

Un embedding (ver figura 2) es la representación numérica densa de tamaño fijo de un dato estructurado o no estructurado (mapear imágenes, entidades o palabras a vectores).

<p align = "center">
<img alt = "imagen1" src = imgs\embeddings.png style="width:500px; height:auto" style= "display: block; margin: 0 auto">
</p>
<p align = "center"> Figura 2.  Ejemplo de <i>embeddings [2] </i>. </p>

### 2.1 ***Word embeddings***

Las palabras de significado similar tendrán una representación similar como ***embeddings***.

### 2.2 ***N-gram***

Subsecuencia de N elementos de una secuencia dada.

### Implementación de ***embeddings***
Las principales técnicas de implementación de ***embeddings*** se mencionan a continuación:

a. *Continous bag of words model* (CBOW)
b. *Skip-gram*

### 3. Redes Neuronales Recurrentes (RNN)
La red neuronal recurrente (ver figura 3) es un tipo de neurona con un estado interno (o memoria) de manera que la información del pasado influye en los resultados futuros.

a. Se usa principalmente para resolver problemas de secuencia, en donde el valor anterior está relacionado con el valor futuro.
b. Permite construir modelos cuyos vectores de entrada o salida no posean una dimensión fija.

<p align = "center">
<img alt = "imagen1" src = imgs\RNN.png style="width:500px; height:auto" style= "display: block; margin: 0 auto">
</p>
<p align = "center"> Figura 2.  Red neuronal recurrente (RNN) [3]. </p>

### Trabajos prácticos desarrollados
Durante la materia se desarrollaron los siguientes ejercicios:
a. Vectorización de documentos/corpus
b. Desarrollo de un *bot* con *deep learning*
c. Predicción de palabras
d. Análisis de sentimientos
e. *Bot* con preguntas y respuestas





---
## Referencias
[1] [Hashem, Istiaque & Islam, Minhajul & Haque, Shazid & Jabed, Zobaidul & Sakib, Nazmus. (2021). A Proposed Technique for Simultaneously Detecting DDoS and SQL Injection Attacks. International Journal of Computer Applications. 183. 50-57. 10.5120/ijca2021921428. 
](https://www.researchgate.net/figure/Tokenization-method-in-NLP-28_fig1_352658333.com)

[2] [What are vector embeddings](https://www.pinecone.io/learn/vector-embeddings/)

[3] [Deep Learning: Recurrent Neural Networks](https://www.google.com/url?sa=i&url=https%3A%2F%2Fmedium.com%2Fdeeplearningbrasilia%2Fdeep-learning-recurrent-neural-networks-f9482a24d010&psig=AOvVaw0ouBXVqziBgHdARpdkqunV&ust=1697159929597000&source=images&cd=vfe&opi=89978449&ved=0CBMQjhxqFwoTCLCF08ir74EDFQAAAAAdAAAAABAH)


![footer](doc/LogoFooter.png)
