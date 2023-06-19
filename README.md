# English-telugu_transformer

Language translation has been a challenging task in natural language processing (NLP) for many years. Traditional approaches to machine often required human intervention and were limited in their ability to handle complex sentence structures and idiomatic expressions. However, recent advances in deep learning techniques have revolutionized the field of machine translation, and the transformer architecture has emerged as a dominant approach.

The aim of the project is to build a model using transformer architecture to translate text from one language to another language. The main components of a translation model using a transformer includes Embedding, Positional Encoding, Self-Attention, Encoder, Decoder, and a Linear Projection. The Transformer model has many advantages over traditional natural language processing techniques such as parallel processing, self- attention, faster training, etc. The model will be trained on large corpus of the text data including both source language and translated language and we plan to experiment with different hyperparameters and optimization techniques to improve the translation accuracy.


The Transformer architecture consists of an encoder and a decoder, both of which are composed of multiple layers of self-attention and feedforward neural networks. The self-attention mechanism allows the model to attend to different parts of the input sequence when generating the output sequence. This is done by computing a weighted sum of the encoder outputs, where the weights are learned based on the similarity between the query, key, and value vectors. Positional encodings are used to provide the model with information about the position of each token in the sequence, which is important for capturing temporal dependencies.



Since the data that we wanted wasn’t readily available on the internet, we prepared our own dataset that consists of the languages English and Telugu.
Our goal for this project was to implement a translator using transformer on this data that translates the text from English to Telugu.
For the creation of this data we collected and aligned various texts that are of high quality and can be of good use of this project.
The data consists of sentences and words that belong to diverse topics that range from simple sentences and words such as “how are you?”, “Cat” to “On Earth, a body of water is considered a lake when it is inland, not part of the ocean, is larger and deeper than a pond, and is fed by a river.” so that the transform doesn’t perform only one genre.



