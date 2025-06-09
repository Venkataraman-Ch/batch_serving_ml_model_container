# BatchServing ML ModelContainer

### 
Purpose:  The repository facilitates batch serving of machine learning models through a Dockerized setup. 
It includes scripts to train models using three classification algorithms
—Linear Discriminant Analysis (LDA)
-Neural Network (NN)
-Decision Tree Classifier (DT). 
---------------------------------------------------------

## Technical details:
### 
train.py uses 3 different classification models (LDA, NN, DT)) to train the model for training data ('train.csv')
All 3 model joblib files will be saved under modelfiles folder.
Model files will be used by test data ('test.csv') to predict scope and classification report in inference.py
Docker image will be created using Dockerfile with required requirements as per 'requirements.txt'

### The technologies include:
Machine Learning Frameworks: It implements LDA, Neural Networks, and Decision Tree Classifiers for classification tasks.
Joblib: Models are serialized and stored using joblib for efficient reuse.
Dockerization: The use of a Dockerfile ensures the environment is reproducible, making it easier to share and deploy the system.
Data Handling: The system is designed to process training and test data via CSV files, emphasizing batch processing.
These features collectively make it a streamlined solution for deploying machine learning models in batch-serving scenarios.

### Happy coding and learning :)
