# MicrosoftAI
# BaseLine Folder
BaseLine folder consists of baseline models provided by the organizer.
It consists of a Convolutional Neural Net model and a BM25 score based model.

# cleanText.ipynb
Consists of preprocessing steps carried out to remove noise as it doesn't contain much information about query and passages and make data suitable for word embedding based model.

# Boosting.ipynb
XGBoost model based on features such as word count,character count,distance between query and passage,tf-idf, bm 25 scores generated from baseline bm25 model. Achieves higher accuracy than both CNN and BM25 baseline model. 
