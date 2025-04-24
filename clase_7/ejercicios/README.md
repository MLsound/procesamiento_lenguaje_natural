# AI-NLP-Projects
![img1](/logoFIUBA.jpg)

# AI-Specialization - Buenos Aires University (UBA)
## Natural Language Processing (NLP) - Course Projects
Projects completed for the Natural Language Processing (NLP) course as part of the Artificial Intelligence (AI) Specialization at the University of Buenos Aires (UBA).

# Profesores
* Dr. Rodrigo Cardenas Szigety (2022-actual)\
* Dr. Nicolás Vattuone (2025-actual)\
* Esp. Ing. Hernán Contigiani (2021-2022)


## Desafío 1 — Vectorization
**Dataset:** data from **20 Newsgroups**, a collection of over 18.8k posts categorized by news representing diverse topics (e.g., politics, religion, computer hardware, sports).
* Vectorize documents and analyze similarity between them.
* Implemented and trained Naïve Bayes classification models (Multinomial and ComplementNB) aiming to maximize macro F1-score on the test set.
* Transposed the document-term matrix to obtain a term-document matrix.
[Link on Github](https://github.com/MLsound/procesamiento_lenguaje_natural/blob/main/clase_1/ejercicios/Desafio_1.ipynb)

## Desafío 2 —  Embeddings (Tango dataset)
**Dataset:** for this project, I built a **custom dataset** consisting of over 3700 tango lyrics in spanish language (Rioplatense variant, including Lunfardo slang). To build this dataset, I scraped the website [*todotango.com*](https://www.todotango.com/musica/obras/letras/-/7/Tango/)
The project focused on exploring word embeddings using this custom tango lyrics dataset.
* Trained custom word vectors using Gensim based on the concepts learned in class.
* Explored the embedding space by testing terms of interest and analyzing semantic similarities.
* Formulated and tested word analogy tasks.
* Visualized the resulting embeddings.
* Derived insights and conclusions from the embedding analysis.
[Link on Github](https://github.com/MLsound/procesamiento_lenguaje_natural/blob/main/clase_2/ejercicios/Desafio_2.ipynb)


## Desafío 3 — Recurrent Neural Networks (LSTM & GRU models)
**Dataset:** I also worked with my custom Tango dataset for this project, developed for the previous one.
This project involved building a language model using Recurrent Neural Networks.
* Selected a text corpus for training the language model.
* Performed necessary pre-processing steps: tokenization, dataset structuring, and splitting into training and validation sets.
* Designed and implemented language models using recurrent neural network architectures (LSTM & GRU).
* Generated new sequences using the trained models, exploring different generation strategies: greedy search, deterministic beam search, and stochastic beam search. Analyzed the impact of temperature on the quality of generated sequences during stochastic beam search.
[Link on Github](https://github.com/MLsound/procesamiento_lenguaje_natural/blob/main/clase_3/ejercicios/Desafio_3.ipynb)

## Desafío 4 — LSTM QA Bot
**Dataset:** data from the **ConvAI2** *(Conversational Intelligence Challenge 2)* dataset, which contains English conversational data.
This project focused on building a Question Answering (QA) Bot.
* Developed an LSTM-based Question Answering (QA) Bot.
* Prepared and integrated word embeddings to transform input tokens into vector representations.
* Trained an encoder-decoder model architecture on the processed data.
* Experimented with the model's performance and inference process, running encoder and decoder separately to understand their roles.
[Link on Github](https://github.com/MLsound/procesamiento_lenguaje_natural/blob/main/clase_6/ejercicios/Desafio_4.ipynb)

# Thanks for your interest!

If you have any questions, please email me at _ml.sound.dev@gmail.com_.