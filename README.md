# Neural_Machine_Translation

### What is our aim?

In this project we aim to map the input German sentences to English sentences as output having the same semantic meaning, this is commonly known as machine translation.

### What do you mean by Machine Translation?

In machine translation we aim to convert the source text in one language to target text in another language using statistical/neural models.
When we use neural network models to perform machine translation it is called neural machine translation.


<p align="center">
  <img src=./image.png width = "450" height = "300"/>
</p>

* Here we use the concept of sequence to sequence modelling which is a special class of recurrent neural networks architecture that is used to solve complex language problems.  

* The sequence to sequence model aims to map a given input to it's corresponding output where both input and output are typically sentences and their length may differ.

* We use the encoder-decoder architecture for our problem statement:

<p align="center">
  <img src=./EncoderDecoder.png width = "350" height = "200"/>
</p>
