# About 

This repository contains the code that generates our NER results for both our selected BERT model and QuickUMLS model, along with a few outputs graphs from the linked paper.

### Data

The data, including the output NER data for bothe models, the original Chatdoctor data, is hosted on the Dropbox Folder linked below.

https://www.dropbox.com/scl/fo/bljx8a3gkg0lwp0oprq6s/AJDciRaXz5hSc0S9T9oPmrc?rlkey=byf1rqj6y03nvnj5betx1vhu9&st=iprbly6z&dl=0

The contents of the Dropbox folder simply need to be added to the current directory to be used.

The dataset of dialogues analyzed is:
HealthCareMagic-100k.json

The key result files are:
Combined_BERT_NER.pkl (results of running our selected BERT on our dialogue dataset)
Combined_QuickUMLS_NER.pkl (results of running QuickUMLS on our dialogue dataset)