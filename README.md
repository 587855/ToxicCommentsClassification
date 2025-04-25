# Toxic Comments Classification

Project for DAT255 - Deep Learning Engineering at HVL  
This project uses a BERT model to classify online comments as either toxic or non-toxic. The model was trained on a balanced subset of the Civil Comments dataset.

🔗 Link to live Gradio app:  
https://huggingface.co/spaces/fredrikcrook/Toxic_Comment_Classifier

## Features

- Uses `bert-base-uncased` from Hugging Face Transformers
- Trained on 100,000 cleaned and balanced comments
- Evaluated with precision, recall, F1-score and accuracy
- Compared against logistic regression, Naive Bayes, LSTM and GRU baselines
- Deployed with Gradio and Hugging Face Spaces
