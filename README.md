# NLP-programs

This repository contains Python programs for Natural Language Processing (NLP). It covers text preprocessing, feature extraction, machine learning, deep learning, and transformer-based applications.

## Program 1 - Tokenization of Sentences and Words using NLTK and spaCy

This program demonstrates tokenization using NLTK and spaCy. Tokenization is the process of breaking text into smaller units, such as sentences and words.

**Libraries Used:** NLTK, spaCy

## Program 2 - Stemming and Lemmatization on Sample Text

This program demonstrates stemming and lemmatization on sample words using NLTK. Stemming reduces words to their root form by removing prefixes or suffixes, while lemmatization converts words into their meaningful dictionary forms.

**Library Used:** NLTK

## Program 3 - Stop-word Removal from a Document

This program removes common English stop words from a document using NLTK. Stop words are frequently occurring words such as "the", "is", "and", and "of" that may be removed during text preprocessing.

**Library Used:** NLTK

## Program 4 - Part-of-Speech (POS) Tagging of a Given Sentence

This program performs Part-of-Speech (POS) tagging using NLTK. POS tagging assigns grammatical categories to words based on their context in a sentence. These categories include nouns, verbs, adjectives, adverbs, pronouns, and prepositions.

**Library Used:** NLTK

## Program 5 - Parsing and Chunking using RegEx and spaCy

This program demonstrates parsing and chunking using regular expressions (RegEx) and spaCy. Parsing analyzes the grammatical structure of a sentence, while chunking groups related words into meaningful phrases, such as noun phrases.

**Libraries Used:** spaCy, RegEx

## Program 6 - Named Entity Recognition (NER) using spaCy

This program identifies and classifies named entities in text using spaCy. It recognizes entities such as people, organizations, geographical locations, dates, monetary values, and events.

**Library Used:** spaCy

## Program 7 - Coreference Resolution using neuralcoref or Similar Tools

This program demonstrates the identification of references to entities in text. Coreference resolution determines when different expressions, such as a person's name and a pronoun, refer to the same entity.

**Libraries Used:** spaCy, neuralcoref or similar tools

## Program 8 - Bag-of-Words (BoW) Vectorization and Representation

This program converts text documents into numerical vectors using the Bag-of-Words model. It represents text based on word occurrence counts and helps prepare textual data for machine learning algorithms.

**Library Used:** Scikit-learn

## Program 9 - TF-IDF Implementation and Comparison with BoW

This program implements Term Frequency-Inverse Document Frequency (TF-IDF) and compares it with the Bag-of-Words model. TF-IDF assigns weights to words based on their frequency in a document and their importance across a collection of documents.

**Library Used:** Scikit-learn

## Program 10 - N-Gram Model Generation

This program generates unigrams, bigrams, and trigrams from a text corpus. Unigrams contain one word, bigrams contain two consecutive words, and trigrams contain three consecutive words.

**Libraries Used:** NLTK, Scikit-learn

## Program 11 - Cosine Similarity between Text Documents

This program calculates cosine similarity between text documents. Cosine similarity measures how similar two documents are by comparing the angle between their numerical vector representations.

**Libraries Used:** Scikit-learn, NumPy

## Program 12 - Word2Vec Word Embeddings using Gensim

This program trains a Word2Vec model on a custom text corpus using Gensim. Word2Vec generates numerical word embeddings that capture relationships and similarities between words.

**Library Used:** Gensim

## Program 13 - GloVe Embeddings Loading and Vector Representation

This program loads pre-trained GloVe word embeddings and represents words as numerical vectors. These embeddings capture semantic relationships between words based on their usage in a large text corpus.

**Library Used:** Gensim

## Program 14 - Text Similarity using Word Mover's Distance (WMD)

This program calculates text similarity using Word Mover's Distance. WMD measures the minimum semantic distance required to transform the word distribution of one document into that of another.

**Libraries Used:** Gensim, POT

## Program 15 - Text Classification using Naïve Bayes/SVM with TF-IDF

This program classifies text documents into predefined categories using machine learning algorithms such as Naïve Bayes or Support Vector Machine (SVM). TF-IDF converts text into numerical features before classification.

**Library Used:** Scikit-learn

## Program 16 - Sentiment Analysis using TextBlob and VADER

This program performs sentiment analysis using TextBlob and VADER. It analyzes text to identify positive, negative, or neutral sentiment and calculates sentiment scores.

**Libraries Used:** TextBlob, VADER Sentiment

## Program 17 - Topic Modeling using Latent Dirichlet Allocation (LDA)

This program applies Latent Dirichlet Allocation to discover hidden topics in a collection of documents. LDA identifies groups of related words that represent different topics.

**Library Used:** Scikit-learn

## Program 18 - Topic Modeling using Latent Semantic Analysis (LSA)

This program performs topic modeling using Latent Semantic Analysis. LSA applies Singular Value Decomposition (SVD) to a document-term matrix to identify underlying semantic patterns in text.

**Libraries Used:** Scikit-learn, NumPy

## Program 19 - Opinion Mining on Product/Service Reviews

This program performs opinion mining on product or service reviews. It analyzes customer feedback to determine whether opinions are positive, negative, or neutral.

**Libraries Used:** TextBlob, NLTK

## Program 20 - Information Extraction from Structured and Unstructured Documents

This program demonstrates information extraction from structured and unstructured text. It identifies useful information, such as names, organizations, locations, dates, and other relevant entities.

**Libraries Used:** spaCy, Regular Expressions

## Program 21 - Information Retrieval System with Ranking using TF-IDF

This program implements a basic information retrieval system that searches documents based on a user query. It uses TF-IDF and cosine similarity to rank documents according to their relevance to the query.

**Library Used:** Scikit-learn

## Program 22 - Sequence Classification using RNN/LSTM

This program demonstrates sequence classification using a Recurrent Neural Network (RNN) or Long Short-Term Memory (LSTM) network. These models process sequential data and learn patterns in text for classification tasks.

**Libraries Used:** TensorFlow, Keras

## Program 23 - Implementing a Basic Attention Mechanism

This program demonstrates a basic attention mechanism for neural networks. Attention helps a model focus on relevant parts of an input sequence when processing textual information.

**Libraries Used:** TensorFlow, Keras

## Program 24 - Fine-Tuning BERT for Text Classification using Hugging Face

This program demonstrates the use of BERT for text classification using the Hugging Face Transformers library. Fine-tuning adapts a pre-trained language model to a specific classification task using labeled data.

**Libraries Used:** Hugging Face Transformers, PyTorch

## Program 25 - Sentence Embeddings using BERT and GPT-2

This program generates numerical representations of sentences using pre-trained BERT and GPT-2 models. Sentence embeddings represent textual information in vector form and can be used for similarity comparison and other NLP tasks.

**Libraries Used:** Hugging Face Transformers, PyTorch

## Program 26 - Text Generation using GPT-2

This program demonstrates text generation using the pre-trained GPT-2 language model. Given an input prompt, the model generates additional text based on patterns learned during training.

**Library Used:** Hugging Face Transformers

## Program 27 - Named Entity Recognition using Transformers (BERT)

This program performs named entity recognition using a pre-trained transformer model based on BERT. It identifies entities such as person names, organizations, and locations in textual data.

**Library Used:** Hugging Face Transformers

## Program 28 - Machine Translation using MarianMT or T5

This program demonstrates machine translation, which converts text from one language into another. Pre-trained models such as MarianMT or T5 can be used to perform translation tasks.

**Library Used:** Hugging Face Transformers

## Program 29 - Text Summarization using BART or T5

This program demonstrates automatic text summarization using language models such as BART or T5. Text summarization generates a shorter version of a document while preserving its main ideas.

**Library Used:** Hugging Face Transformers

## Program 30 - Chatbot Development using a Pre-trained Transformer

This program demonstrates the development of a chatbot using a pre-trained conversational transformer such as DialoGPT. The chatbot generates responses based on user input and maintains conversational context where supported.

**Library Used:** Hugging Face Transformers

## Program 31 - Automatic Document Classification and Separation using ML

This program classifies documents into predefined categories using machine learning techniques. Based on the predicted category, documents can be grouped or separated automatically.

**Libraries Used:** Scikit-learn, NumPy

## Program 32 - Hybrid Probabilistic and FSM-Based Sequence Modeling for Document Boundary Detection

This program demonstrates document boundary detection using a combination of probabilistic techniques and a Finite State Machine (FSM). It identifies document sections or boundaries based on textual patterns and predefined state-transition rules.

**Libraries Used:** Python, Regular Expressions

## Technologies Used

- Python
- NLTK
- spaCy
- Scikit-learn
- Gensim
- TensorFlow and Keras
- Hugging Face Transformers
- PyTorch
- NumPy
- TextBlob
- VADER Sentiment

## How to Run the Programs

1. Clone or download this repository.
2. Open the required Python file or notebook in Google Colab, Jupyter Notebook, or VS Code.
3. Install the required libraries.
4. Download any required language models or pre-trained models.
5. Run the program and observe the output.

## Learning Outcomes

By completing these programs, students will understand NLP preprocessing, feature extraction, word embeddings, text similarity, machine learning-based text classification, sentiment analysis, topic modeling, deep learning, transformer models, and various real-world NLP applications.

## Author

**Divyanshi Goyal**

---

*This repository is intended for educational purposes and practical learning in Natural Language Processing.*


