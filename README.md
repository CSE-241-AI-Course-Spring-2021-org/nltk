# Lab Task-5: Isolated Word Morphological Analysis

In this lab task, Isolated Word Morphological Analysis has been done on the two languages.


## RNN
    Recurrent Neural Network is a generalization of feedforward neural network that has an internal memory. RNN is recurrent in nature as it performs the same function for every input of data while the output of the current input depends on the past one computation. After producing the output, it is copied and sent back into the recurrent network. For making a decision, it considers the current input and the output that it has learned from the previous input.
     RNNs can use their internal state (memory) to process sequences of inputs

## BI-LSTM
    Long Short-Term Memory (LSTM) networks are a modified version of recurrent neural networks, which makes it easier to remember past data in memory. The vanishing gradient problem of RNN is resolved here. LSTM is well-suited to classify, process and predict time series given time lags of unknown duration.

### File architechure

The main directory consists of three directories
- Chunking
    - RNN
    - BI-LSTM 
- NER
    - RNN
    - BI-LSTM 
- POS
    - RNN
    - BI-LSTM 

### POS

Tagging is a kind of classification that may be defined as the automatic assignment of description to the tokens. Here the descriptor is called tag, which may represent one of the part-of-speech, semantic information and so on.

Pos tagging is defined as the process of assigning one of the parts of speech to the given word. It is generally called POS tagging. In simple words, we can say that POS tagging is a task of labelling each word in a sentence with its appropriate part of speech.
        
- Implemented POS Tagger using both RNN and LSTM
- Dataset used for the training is CoNLL2000
- In each folder there are the respective jupyter files and models

### CHUNKING

Chunking is a process of extracting phrases from unstructured text, which means analyzing a sentence to identify the constituents(Noun Groups, Verbs, verb groups, etc.) However, it does not specify their internal structure, nor their role in the main sentence.

It works on top of POS tagging. It uses POS-tags as input and provides chunks as output.

- Implemented Chunking using both RNN and LSTM

### NER

Named entity recognition (NER) — sometimes referred to as entity chunking, extraction, or identification — is the task of identifying and categorizing key information (entities) in text. An entity can be any word or series of words that consistently refers to the same thing. Every detected entity is classified into a predetermined category. 

- Implemented NER using RNN and Bi-LSTM
- Models have achieved a greater accuracy of about 98.59%

### Conclusion
- In chunking we get very high accuracy using Bi-Lstm and almost similiar accuracy using RNN when compared with CRF++ implementation.
- In POS_tagging we get very high accuracy using Bi-Lstm and almost similiar accuracy using RNN when compared with CRF++ implementation.
- IN NER we get high accuaracy using Bi-Lstm and almost similiar accuracy using RNN when compared with CRF++ implementation.
