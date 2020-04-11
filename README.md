# DSND-CapstoneProject-SatelliteImageCNN

The repository is dedicated to an independent data science project, for completion of the Udacity Data Science Nanodegree. This project leverages the application of transfer learning on satellite image data. The task is to successfully predict the type of land coverage in a given satellite photo. 

# I. Requirements & Dependencies:

- Python 3.x

- tensorflow==1.12.0

- keras==2.3.0

- flask==1.0.2

Model training was completed in a GPU-enabled Kaggle kernel.  

# II. Data:
Data is provided publicly by the Deutsches Forschungszentrum für Künstliche Intelligenz (German Research Center for Artificial Intelligence). 

The dataset contains 27,000 64x64p Sentinel-2 Images in RGB mode of various land classifications. The dataset is divided into 10 class labels ranging from natural to urban geographic features. The data can be downloaded, and passing the path to the data's directory as an argument to preprocessing.py will split the dataset into training and testing directories, based on a provided 'test_size' argument. Class size distributions and labels are explored in the jupyter notebook.

# III. Files:

  - repo
  
    -- \predict.py: command-line application to predict land cover on an image file
    
    -- \preprocessing.py: command-line application to split the dataset directory into training & testing directories
    
    -- \train.py: command-line application for training a model
    
    -- \utils.py: utility file
    
    -- \EUROSAT_NB.ipynb: data exploration, model training and evaluation
    
    -- \api
    
      -- \app.py: Deploy trained model to API endpoint using Flask

      -- \run_prediction.py: command-line application for predicting land cover on an image file

# IV. Directions:


