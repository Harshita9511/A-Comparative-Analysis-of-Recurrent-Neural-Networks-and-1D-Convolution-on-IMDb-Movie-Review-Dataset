# A Comparative Analysis of Recurrent Neural Networks and 1D Convolution on IMDb Movie Review Dataset

<img src="/image.jpg" width="1000" height="300" />
<div align="justify">

Recurrent neural networks, also known as RNNs, are a class of neural networks that allow previous outputs to be used as inputs while having hidden states. RNN models are mostly used in the fields of natural language processing and speech recognition.<br /> 
The vanishing and exploding gradient phenomena are often encountered in the context of RNNs. The reason why they happen is that it is difficult to capture long term dependencies because of multiplicative gradient that can be exponentially decreasing/increasing with respect to the number of layers.<br /><br />
*Gated Recurrent Unit (GRU)* and *Long Short-Term Memory units (LSTM)* deal with the vanishing gradient problem encountered by traditional RNNs, with LSTM being a generalization of GRU.<br /><br />
*1D Convolution* layer creates a convolution kernel that is convolved with the layer input over a single spatial (or temporal) dimension to produce a tensor of outputs. It is very effective for deriving features from a fixed-length segment of the overall dataset. A 1D CNN works well for natural language processing (NLP).<br /><br />

## Dataset
TensorFlow Datasets is a collection of datasets ready to use, with TensorFlow or other Python ML frameworks, such as Jax. All datasets are exposed as tf.data.Datasets , enabling easy-to-use and high-performance input pipelines.<br /><br />
**imdb_reviews**
This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. It provides a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. 
</div>
