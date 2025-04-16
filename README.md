**NLP and Deep Learning Projects**

Name: Bharadwaj Ketham
Student ID: 700759639

Project Overview
This repository features a collection of mini-projects focused on core concepts in Natural Language Processing (NLP) and Deep Learning. Each module demonstrates a specific technique, ranging from text preprocessing and named entity recognition to attention mechanisms and sentiment classification using pre-trained models.

Contents
1. NLP Preprocessing Pipeline

2. Named Entity Recognition (NER) with SpaCy

3. Scaled Dot-Product Attention

4. Sentiment Analysis using HuggingFace Transformers

5. Conclusion

**1. NLP Preprocessing Pipeline**
Goal: Develop a simple preprocessing workflow to prepare text for NLP tasks.

What’s Implemented:

Tokenization: Splits the input sentence into individual words.

Stopword Removal: Filters out commonly used words (like "is", "the", "in") to retain only informative terms.

Stemming: Reduces each word to its root form (e.g., "playing" becomes "play").

Outcome:
The pipeline outputs:

A list of raw tokens

Tokens with stopwords removed

Stemmed versions of the remaining tokens

**2. Named Entity Recognition (NER) with SpaCy**
Goal: Identify and extract entities from a sentence using SpaCy’s pre-trained NER model.

What’s Implemented:

Loaded SpaCy’s English NER model.

Ran the model on an example sentence.

Extracted and displayed the entities, including their labels (e.g., PERSON, ORG, GPE) and positions in the text.

Example Sentence:
“Barack Obama served as the 44th President of the United States and won the Nobel Peace Prize in 2009.”

Expected Output:
Entities like "Barack Obama", "United States", and "2009", along with their labels and token positions.

**3. Scaled Dot-Product Attention**
Goal: Manually implement the scaled dot-product attention mechanism, a key component of transformer models.

Steps:

Compute the dot product between the query (Q) and the transpose of the key (K).

Scale the result by dividing it by the square root of the dimensionality of the key vectors.

Apply softmax to the scaled scores to get attention weights.

Multiply the attention weights with the value (V) matrix to produce the output.

Outcome:

A matrix of attention weights

The resulting output after applying attention to the value matrix

**4. Sentiment Analysis using HuggingFace Transformers**
Goal: Use a pre-trained transformer model to determine the sentiment of a given sentence.

What’s Implemented:

Loaded HuggingFace’s sentiment analysis pipeline.

Passed in a sentence for analysis.

Retrieved the sentiment label (e.g., POSITIVE/NEGATIVE) and the confidence score.

Example Input:
“Despite the high price, the performance of the new MacBook is outstanding.”

Expected Output:

Sentiment: POSITIVE

Confidence Score: e.g., 0.9998

**Conclusion**
This project demonstrates several foundational techniques in NLP and Deep Learning:

- Text Preprocessing: A basic pipeline for cleaning and preparing text data.

- NER: Entity extraction using SpaCy’s state-of-the-art models.

- Attention Mechanism: A simplified implementation of the attention mechanism used in transformer architectures.

- Sentiment Analysis: Leveraging transfer learning through pre-trained models for text classification.

These modules offer a hands-on introduction to essential building blocks in modern NLP systems, paving the way for more advanced applications and research.
