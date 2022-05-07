# NLP-Sarcasm-Text-classfication

The general field that studies natural language is called natural language understanding. Most of today’s algorithms are unconcerned with any kind of actual understanding of the language they process. Instead, they extract statistics from the data and use those statistics as the basis for tasks like answering questions or
generating text. These techniques are generally called natural language processing.

## Common Natural Language Processing Tasks

Many methods help the NLP system to understand text and symbols. They are text classification, vector semantic, word embedding, probabilistic language model, sequence labeling, and speech reorganization.

The applications of natural language algorithms are commonly called tasks. Here are some popular tasks:

 * **Sentiment Analysis**: Given opinionated text like a movie review, determine whether the overall sense is positive or negative.
 * **Translation**: Turn text into another language.
 * **Answer Questions**: Answer questions about the text, like who is the hero, or what actions occurred.
 * **Summarize or Paraphrase**: Provide a short overview of the text, emphasizing the main points.
 * **Generate New Text**: Given some starting text, write more text that seems to follow from it.
 * **Logical Flow**: If a sentence first asserts a premise and the following sentence asserts a conclusion based on that premise, determine whether the conclusion logically follows from the premise.

The main goal of natural language processing is to derive information from natural language.

![NLP](https://user-images.githubusercontent.com/62169942/167230648-eb9c8a50-8c99-4fe8-882c-44ed093bd82b.png)

Process of natural language processing

* Downloading a text dataset
* Visualizing text data
* Converting text into numbers using tokenization
* Turning our tokenized text into an embedding
* Modelling a text dataset
  * Starting with a baseline (TF-IDF)
  * Building several deep learning text models
    * Dense, LSTM, GRU, Conv1D,Dropout, Transfer learning
  * Fit the model

In this project, after tokenize - Embedding process, l have used Bidirectional with LSTM and SpatialDropout1D. Using SpatialDropout1D after LSTM improve accuracy and decrease loss.
