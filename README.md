# Author-Writings-Identification-with-NLP-and-Topic-Modelling

Share code and discuss insights to identify horror authors from their writings

The dataset contains text from works of fiction written by spooky authors of the public domain: Edgar Allan Poe, HP Lovecraft and Mary Shelley. The data was prepared by chunking larger texts into sentences using CoreNLP's MaxEnt sentence tokenizer, so you may notice the odd non-sentence here and there. The objective is to accurately identify the author of the sentences in the test set.

File descriptions

train.csv - the training set

test.csv - the test set


Data fields

id - a unique identifier for each sentence

text - some text written by one of the authors

author - the author of the sentence (EAP: Edgar Allan Poe, HPL: HP Lovecraft; MWS: Mary Wollstonecraft Shelley)
