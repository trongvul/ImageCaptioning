Automatic image captioning is a area of research in artificial intelligence that incorporates insights and ideas from both machine vision and natural language processing. This work involves the development of an encoder-decoder model that takes an image as input and generates a corresponding description in English. The encoder uses a convolutional neural network (CNN) to create a new representation of the image as a 2D vector that serves as a visual feature. The decoder contains a recurrent neural network (RNN) to generate word after word based on these visual features. 

In addition, many different techniques were used to increase the performance of the model to achieve the expected result. 

- Transfer learning with EfficientNet for visual feature extraction.
- Data augmentation
- Application of pre-trained word embedding with GloVe for semantic language features.
- Positional word embedding
- Bahdanau attention mechanism

The model achieves 57.9 BLEU-1 score on the Flickr8k dataset. Moreover, the generated image captions seem reasonable and appropriate in terms of qualitative evaluation.
