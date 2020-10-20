# NLP-project

I use an IPython notebook with instructions and some code prepared.

- I use Python 3 and Tensorflow 1.0. And it work with many libraries, e.g. NLTK, Scikit-learn, Gensim, Tensorflow, etc.

## Use Google Colab

Use Google Colab where you can install or import all necessary libraries. Instructions on how to run code on Colab are provided in [Here](https://github.com/hse-aml/natural-language-processing, "Class GitHub repository").

### Predict tags on StackOverflow with linear models

In this project learn how to predict tags for posts from StackOverflow. To solve this task I used multilable classification approach.

#### Libraries

- Numpy: a package for scientific computing.
- Pandas: a library providing high-performance, easy-to-use data structures and data analysis tools for the Python
- scikit-learn: a tool for data mining and data analysis
- NLTK: a platform to work with natural language

---

### Recognize named entities on Twitter with LSTMs

In this project, will use a recurrent neural network to solve Named Entity Recognition(NER) problem. NER is a common task in natural language processing systems. It serves for extraction such entities from the text as persons, organizations, locations, etc. 

#### Libraries 

- Tensorflow: In this, will use Tensorflow 1.15.0.

```
!pip install tensorflow==1.15.0
```

- Numpy

### Find duplicate questions on StackOverflow by their embeddings

In this task, learn how to calculate a similarity for pieces of text. Using this approach you will know how to find duplicate questions from StackOverflow.

#### Libraries

- StarSpace
- Gensim
- Numpy
- scikit-learn
- NLTK

### seq2seq model

We can see how to use neural networks to solve sequence-to-sequence prediction tasks.Seq2seq models are very popular these days because they achieve great result in Machine Translation, Text Summarization, Conversational Modeling and more.

### StackOverflow assistant bot

combine everything before tasks to construct a dialogue chat bot, which will be able to:

- answer programming-related questions (using StackOverflow dataset)
- chit-chat and simulate dialogue on all non programming-related questions 

For a chit-chat mode will use a pre-trained neural network engine available from ChatterBot. 