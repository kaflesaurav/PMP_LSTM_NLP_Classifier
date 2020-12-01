# PMP_LSTM_NLP_Classifier
Postgraduate Major Project - An LSTM based approach to classification of mental health issues using Natural Language Processing

## Abstract
The success of LSTM networks in various natural language processing has been evident in the researches in recent years. This project is an attempt to apply the power of LSTM models to classify the natural language description of a user’s mental health issue into pre-defined categories. It is a classification project where the LSTM model will extract the sequential information from the natural language text and use that to classify the samples. The data used for the project contained the text description of mental health issue along with its ground truth category. The text sample itself was subjected to text processing techniques within NLP and LSTM was built on numericized data. The results of the project show that such a system is possible. The model resulted in 73% accuracy before overfitting and also showed promising potential for better result with availability of a larger dataset. Transfer learning using BERT was tried on the dataset too which showed signs of convergence during training but failed to generalise. It was concluded that for a small dataset like the one used for this project simpler models are the go-to option which leaves scope for further research in training BERT on a similar larger dataset.

See full report at:
https://github.com/kaflesaurav/PMP_LSTM_NLP_Classifier/blob/main/SSID_0925739_Project_Report.pdf

See jupyter notebook at:
https://github.com/kaflesaurav/PMP_LSTM_NLP_Classifier/blob/main/SSID-0925739-PMP-ProjectCode.ipynb
