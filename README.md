#Named Entity Recognition for Furniture Stores
This project focuses on applying Named Entity Recognition (NER) techniques to text data related to furniture stores. It leverages a pre-trained BERT model to classify entities in the text and fine-tunes it on domain-specific data to enhance performance in recognizing important entities such as product names.

###Project Structure
Notebook: NER_furniture_stores.ipynb
This Jupyter Notebook contains the code and steps for training, evaluating, and fine-tuning the NER model. The notebook includes:
Data loading and preprocessing
Model fine-tuning using the BERT-base-cased model
Evaluation of model performance using metrics like precision, recall, F1 score, and accuracy
Saving the fine-tuned model for future use
Key Components
Data Preprocessing: The text data is tokenized and transformed into a format suitable for input into a BERT-based model. The data may include information related to product names, categories, brands, and locations.

###Model Training
The BERT model is fine-tuned for the specific task of NER. The notebook logs warnings related to model initialization, suggesting that some weights were newly initialized. The model is trained over several epochs to improve its performance in entity classification.

###Model Evaluation
The performance of the model is evaluated using the following metrics:

- Precision: The proportion of true positive predictions made by the model.
- Recall: The proportion of actual entities correctly identified by the model.
- F1 Score: The harmonic mean of precision and recall.
- Accuracy: The overall accuracy of the model in entity recognition tasks.

###Model Saving
After training, the best-performing model is saved for future inference and prediction tasks.
