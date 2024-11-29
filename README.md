# Shared task on Natural Language Understanding of Devanagari Script Languages at CHIPSAL@COLING 2025


##### This project was done as a part of the shared task @ https://codalab.lisn.upsaclay.fr/competitions/20000


##### For easy access, I have published the dataset on Kaggle. Please find it using the given link: 
https://www.kaggle.com/datasets/siddhz58/subtasks-dataset/data


### Objectives:
Task A: Devanagari Script Language Identification among Nepali, Marathi, Sanskrit, Bhojpuri, and Hindi.
Task B: Hate Speech Detection in Devanagari Script Language from a dataset of Nepali and Hindi sentences.
Task C: Target Identification for Hate Speech in Devanagari Script Language, for identifying the direction of hate speech towards "individual", "organization" or "community."

### Approach:
Fine-tuning pretrained transformer models trained on devnagiri texts of various Indic languages. Modifying the output head for the three tasks separately.
Playing with multiple models and identifying the best performing model. In the end, I extract the predictions as JSON files and save the model, along with accuracy scores for the same.

###### Pre-trained model used: https://huggingface.co/ibm/ia-multilingual-transliterated-roberta

##### Research publication is in review

