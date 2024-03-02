## Introduction
In this project, the task is to train character-level language models to generate new names in multiple languages. 
Specifically, the focus is on building models for Russian, English, and Swedish languages, assessing their quality, and exploring the transferability between these models.

## Datasets:
Russian names: Two datasets containing female names (capitalized and lowercase) and male names (capitalized and lowercase). The datasets were obtained from https://github.com/Raven-SL/ru-pnames-list/tree/master/lists
English names: Two datasets of US cities' names and pet names compiled from the internet.
Swedish names: A dataset of IKEA product names, all characters being uppercase, was used. The dataset was obtained from https://github.com/jleinonen/ikea-names/tree/master/data

## Processing:
The model utilized in this project is based on A. Karpathy's code, with adjustments made for the specific task in each language.
It employs a character-level approach with a context window of three characters for the next character prediction. The PyTorch library is used to implement the model and training.

## Objective:
The aim of this project is to develop and evaluate character-level language models capable of generating names in multiple languages.
Specifically, the project aims to train models for Russian, English, and Swedish languages to generate names of various entities (e.g., persons, companies, animals).
Assess the quality of generated names based on criteria such as diversity, coherence, and similarity to the original dataset.
Investigate the transferability of models between languages, examining the effectiveness of models trained on one language in generating names for other languages.
Gain insights into the performance of character-level language models across different languages and datasets.
Explore the potential applications of such models in tasks like name generation, text augmentation, and creative content generation.
