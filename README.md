# Readme

## Data
We have used the Chaii dataset and the externally available MLQA and XQUAD datasets. The MLQA and XQUAD datasets need to be preprocessed before use. Run the 'preprocessing/mlqa-xquad-preprocessing-and-eda.ipynb' file to get the data. Two csv files with the names 'mlqa_hindi.csv' and 'xquad.csv' will get generated. Download the chaii dataset from this link: 'https://www.kaggle.com/c/chaii-hindi-and-tamil-question-answering/data' by pressing Download All button. Unzip the downloaded file and that's the chaii dataset.


## BaseLine Model
Place the chaii-dataset folder in '../input/'. Download the pre-trained xlma roberta model from 'https://www.kaggle.com/nbroad/xlm-roberta-squad2'. and store it '../input/'. Then simply run the notebook.

## XLM Roberta
### Fine Tuning
Place the chaii-dataset folder in '../input/'. Place 'mlqa_hindi.csv' and 'xquad.csv' in '../input/mlqa-hindi-processed/'. Then simply run the notebook.
### Inference
Repeat the fine tuning step to get the data. Download the saved model from the fine-tuning and place it in '../input/' and run the notebook.
## MuRIL Large
### Fine Tuning
Place the chaii-dataset folder in '../input/'. Place 'mlqa_hindi.csv' and 'xquad.csv' in '../input/mlqa-hindi-processed/'. Download the pre-trained MuRIL Large dataset from 'https://www.kaggle.com/nbroad/muril-large-pt' and place it in '../input'. Then simply run the notebook.
### Inference
Repeat the fine tuning step to get the data. Download the saved model from the fine-tuning and place it in '../input/' and run the notebook.
## RemBert
### Fine Tuning
Place the chaii-dataset folder in '../input/'. Place 'mlqa_hindi.csv' and 'xquad.csv' in '../input/mlqa-hindi-processed/'. Download the pre-trained RemBERT dataset from 'https://www.kaggle.com/nbroad/rembert-pt' and place it in '../input'. Then simply run the notebook.
### Inference
Repeat the fine tuning step to get the data. Download the saved model from the fine-tuning and place it in '../input/' and run the notebook.