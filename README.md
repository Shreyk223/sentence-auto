# sentence-auto
Sentence Autocompletion Using Machine Learning Models

Project Overview: The project aims to develop a machine learning system that can predict and generate the next words or phrases in each sentence using natural language processing (NLP) techniques. The system will utilize deep learning algorithms to analyse and understand the context of the input sentence and provide accurate and contextually relevant suggestions for completing the sentence.

LSTM MODEL: LSTMs are long short-term memory networks that use (ANN) artificial neural networks in the field of artificial intelligence (AI) and deep learning. In contrast to normal feed-forward neural networks, also known as recurrent neural networks, these networks feature feedback connections.

GRU (Gated Recurrent Unit) Model: GRU is a type of recurrent neural network (RNN) architecture. It is designed to address the vanishing gradient problem that occurs in traditional RNNs. GRU cells have two gates: an update gate and a reset gate. The update gate controls how much of the previous hidden state should be retained, while the reset gate determines how much of the new input should be incorporated. GRUs are computationally efficient and perform well on sequence-based tasks.

CNN (Convolutional Neural Network) Model: CNNs are primarily used for image recognition and computer vision tasks. They consist of convolutional layers that apply filters (kernels) to input data, capturing local patterns. CNNs automatically learn hierarchical features from raw pixel values. Max-pooling layers downsample the feature maps, reducing spatial dimensions. Fully connected layers at the end of the network make predictions based on the learned features.

SimpleRNN: SimpleRNN (Simple Recurrent Neural Network) is a type of recurrent neural network (RNN) architecture that is used for sequential data processing tasks. Unlike more complex RNN variants like LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit), SimpleRNN has a simpler architecture and is computationally less expensive.

The flow of program:
Loading data
Preprocessing the data and Tokenizing
Building and fitting the model on data
Evaluate the model
Predicting(Generating the text)
Saving the model for future applicaitons
