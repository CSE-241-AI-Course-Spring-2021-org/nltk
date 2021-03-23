# Lab Task-6: Isolated Word Morphological Generation

In this lab task, Isolated Word Morphological Analysis has been done for four languages, Hindi, German, bengali and middle-high-german.

### Word Morphological 
Morphology is the study of words and their parts. Morphemes, like prefixes, suffixes and base words, are defined as the smallest meaningful units of meaning. Morphemes are important for phonics in both reading and spelling, as well as in vocabulary and comprehension.

### Morphological Generation
The smallest meaningful word in a sentence or a phrase in any language is known as morpheme. In well-spaced sentences , Morphological Analysis(MA) is the first step in Neuro-Linguistic Programming(NLP), in which a sentence is divided into a sequence of morphemes and then we determine parts of speech of the segmented morpheme.

Morphological generation is just inverse of Morphological analysis. Morphlogical inflection Generation is the task of generating the inflected form of a given lemma corresponding to a particular lingusitic transformation. It is a mechnaism of word formation to express different grammatical categories such as tense, mood, voice , aspect , person , gender , number etc.. 

Here, we are doing morphological generation/inflection for only single language at a time.

### Aim
To do Morphological generation for languages hindi(high resource), bengali(low resource), german(high resource) and middle-high-german(low resource).
The aim of this project is to generate inflected word forms given the lemma and a morphological feature specification. An encoder-decoder model is used, modified by a custom trainer that trains only with the target language resources after aspecific threshold.

### Tools used
- Keras
- tensorflow
- Keras-Applications 
- Keras-Preprocessing
- PyYAML, matplotlib
- scikit-learn
- high resource hindi and german dataset, low resource middle-high-german and bengali dataset.
  
### File Struture
- Main directory is 1907074-Srigadha-Shreyas-Raj-lab-task-6
- In the main directory, you will observe four separate directories for four languages.
- Bangali, Hindi, German and Middle-high-german.
- In each of the respective directory, there is notebook, encoders and decoders along with the output files.


### Results
Results of the four languages are present in the four folders in output files and ipynb files.
