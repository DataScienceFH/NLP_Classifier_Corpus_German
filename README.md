# Natural Language Processing (NLP): Classifier Corpus (focussed on German) | Natural Language Processing (NLP): Classifier-Corpus (speziell für Deutsch)

## Description
This repository hosts a dataset for Natural Language Processing (NLP) applications, specifically focusing on the development and testing of classifiers. It comprises two distinct sets of documents in German: those related to pasta and those not. The dataset is designed to facilitate text classification tasks, offering a substantial ground for training and evaluating models capable of distinguishing thematic content.

The repository contains two primary files:

    Pasta_Messages.txt – Containing 500 German statements/messages related to the topic pasta.
    Non-Pasta_Messages.txt – Consisting of 4,500 German statements/messages unrelated to the topic pasta.

Each file is structured so that every line represents an individual statement/message. Key features of the dataset include:
- Messages have been generated using ChatGPT 4.
- The style of messages mimics real-world internet and chat communication, incorporating punctuation, numbers, emoticons, and other typical elements of online textual conversation.

## Corpus Statistics
Some descriptive corpus statistics are summarized below:

| Description           | Pasta Documents | Non-Pasta Documents | All Documents |
| --------------------- | --------------- | ------------------- | ------------- |
| Total Messages        |       500       |        4,500        |     5,000     |
| Total Words           |      3,491      |       20,072        |    23,563     |
| Unique Words          |      1,064      |        5,809        |     6,443     |
| Average Words per Msg |       6.98      |         8.40        |      8.16     |
| SD Words per Msg      |       1.48      |         9.32        |      8.51     |

## Topic Discrimination and Classifier Performance
A Naive Bayes classifier demonstrated a sufficient discriminative power on this preprocessed dataset, achieving an Area Under the Curve (AUC) of 0.99, underlining the corpus's suitability for NLP classifier development and topic probing.

![grafik](https://github.com/DataScienceFH/NLP_Classifier_Corpus_German/assets/129044997/36d9ac39-3dd4-4214-aeda-4ec536e0d21e)

![grafik](https://github.com/DataScienceFH/NLP_Classifier_Corpus_German/assets/129044997/b1474e8a-8c6c-48b0-b225-5f66b51ea8f1)
