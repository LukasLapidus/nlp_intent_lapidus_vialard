# FastText based model for multiligual Dialogue Act (DA) and Emotion/Sentiment (E/S) classification

Project for the Advanced Natural Language Processing course at CentraleSupélec lectured by Professor Pierre Colombo.

## Objective
The goal of the project is to classify uterrances regarding their intent.

## Context
Dialogue Act (DA) and Emotion/Sentiment (E/S) identification is a crucial domain of research for chatbot like ChatGPT or spoken dialogue system like Alexa.
In this work, we use Deep learning techniques applied to Natural Language Processing (NLP) to classify utterance of transcripted spoken dialogues in different languages. Based on pre-trained models and embedding like FastText, our experiments have various performance depending of the dataset used to train the model

## Datasets

| Dataset name          | Language                                             | Train                    | Valid                    | Test                    |
|--------------------------|----------------------------------------------------|--------------------------|--------------------------|-------------------------|
| mrda                     | English                                           | 83943                    | 9815                     |15470                     |     
| maptask                  | English                                            | 25382                    | 5221                     |5335                    |             
| loria                    | French                                           | 8465                     | 942                      |1047                     |    
| vm2                      | German                                           | 25060                    | 2860                     |2855                     |
| dihana                   | Spanish                                           | 19063                    | 2123                     |2361                     

We will apply the different models on these datasets to have their efficiencies.
