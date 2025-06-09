# BatchServing ML ModelContainer

### 
<p>
Purpose: The repository facilitates batch serving of machine learning models through a Dockerized setup. <br>
It includes scripts to train models using three classification algorithms. <br>
-Linear Discriminant Analysis (LDA) <br>
-Neural Network (NN) <br>
-Decision Tree Classifier (DT)<br>
</p>

### Technologies used:
<p>
Machine Learning Frameworks: It implements LDA, Neural Networks, and Decision Tree Classifiers for classification tasks.<br>
Joblib: Models are serialized and stored using joblib for efficient reuse.<br>
Dockerization: The use of a Dockerfile ensures the environment is reproducible, making it easier to share and deploy the system.<br>
Data Handling: The system is designed to process training and test data via CSV files, emphasizing batch processing.<br>
These features collectively make it a streamlined solution for deploying machine learning models in batch-serving scenarios.<br> 
</p>

### Technical details:
<p>
train.py uses 3 different classification models (LDA, NN, DT)) to train the model for training data ('train.csv')<br>
All 3 model joblib files will be saved under modelfiles folder.<br>
Model files will be used by test data ('test.csv') to predict scope and classification report in inference.py <br>
Docker image will be created using Dockerfile with required requirements as per 'requirements.txt' <br>
</p>
