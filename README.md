# 419IDEAS
  ## Description of Data
    All datasets include sample values for Age, Gender, Pack history, Smoking, FEV1%, Diabetes, Muscular 
      dystrophy, High blood pressure, Atrial fibrillation, and Ischemic heart disease, As well as a label 
      of whether or not the individual has COPD.
    
    COPD Dataset.csv: kaggle datasets download -d prakharrathi25/copd-student-dataset
    
    Simulated Healthy Dataset1.csv: randomly generated healthy male data based on Backman, Helena, et al. 
      “Evaluation of the Global Lung Function Initiative 2012 Reference Values for Spirometry in a Swedish 
      Population Sample.”
    Simulated Healthy Dataset0.csv: randomly generated healthy female data also based on Backman, Helena, et al. 
      “Evaluation of the Global Lung Function Initiative 2012 Reference Values for Spirometry in a Swedish 
      Population Sample.”
    
    COPD Dataset2.csv: combined .csv file of the COPD dataset and healthy datasets
    
    Compressed COPD Dataset.csv: 120 samples from COPD Dataset2 to form an appropriated sized dataset for 
      the specific model built including 60 positive and 60 negative samples

  ## Description of Code
    Binary classification of structured data including numerical and categorical features to predict the 
      risk of COPD. We will use Keras preprocessing layers to normalize the numerical features and vectorize 
      the categorical ones.
