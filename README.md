# Sentence Similarity Prediction Using BERT And The Siamese Architecture

Here our task is to classify pairs of sentences (consisting of a premise and a hypothesis) into three categories - entailment, contradiction, or neutral. 

- <u>Entailment</u>:- Hypothesis is true based on the information in the premise
- <u>Neutral</u>:- Hypothesis very well might be true, but we can’t conclude this based on the information in the premise
- <u>Contradiction</u>:- Hypothesis isn’t true, rather it is the complete opposite of what the premise says

The dataset contains premise-hypothesis pairs in fifteen different languages, including: *Arabic, Bulgarian, Chinese, German, Greek, English, Spanish, French, Hindi, Russian, Swahili, Thai, Turkish, Urdu, and Vietnamese.*

The dataset file contains the ID, premise, hypothesis, and label (0 for entailment, 1 for neutral, 2 for contradiction), as well as the language of the text and its two-letter abbreviation. Our model's job is to predict the label based on the other infos.

The BERT used here specifically is XLM-R developed by Facebook AI designed to perform well on a wide range of natural language processing (NLP) tasks across multiple languages.

Siamese Architecture is followed for designing the model network and is inspired by the research paper 'Bert-based Siamese Network for Semantic Similarity'.
