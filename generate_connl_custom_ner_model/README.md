# Custom Named Entity Recognition (NER) Model for Medical Text

The goal of this repository is to work with Spark NLP for Healthcare and run a Named Entity Recognition (NER) pipeline using provided pre-trained models (ner_clinical and ner_posology) on a public dataset. After generating predictions, you will create a CoNLL file from the predictions and use it to train a custom NER model.

## Dataset
The mtsamples(https://github.com/JohnSnowLabs/spark-nlp-workshop/blob/master/tutorials/Certification_Trainings/Healthcare/data/mtsamples_classifier.csv) dataset used in this project contains medical text data, with labels such as "Test," "Treatment", "Drug and other clinical and posology entities relevant to healthcare applications.

## Prerequisites
- Python Libraries:
- pandas,
- matplotlib
- -tensorflow
- Spark NLP and Spark NLP for Healthcare (licensed).

## Steps to Create Custom NER Model
- Load the Dataset
- Create the Pipeline Components
- Merge NER Outputs and Prioritize Posology
- Build the Pipeline
- Extract and Review Entities in a Readable Format
- Generate CoNLL File
- Saving CoNLL File
- Split the dataset into 80% training and 20% test set
- Custom NER Model Training
- Build NER Model
- Evaluate
- compare with jsl_ner model
- Visualize the predictions of the custom NER model
- comparisons of the model’s performance before and after fine-tuning.
- Error analysis

## File Structure
- Spark_NLP_Healthcare_Pipeline_and_Training_a_Custom_NER_Model.ipynb
- conll2003_text_file.conll
- MedicalNerApproach_974ff3998dce.log: Directory for storing model training logs.

  
