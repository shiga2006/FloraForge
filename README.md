                                                                              FLORAFORGE

 Introduction
This project focuses on the classification of corn leaf disease images using an Attentive Convolutional Gated Recurrent Unit (AC-GRU) with the Seeker optimizer. Additionally, it integrates yield prediction models, recommendation system and alert system to provide comprehensive insights for agricultural decision-making.

Project Structure:


-> Preprocessing
-> Segementation
-> Feature Extraction
-> Otpimization and classification


Important links:
Datasets link - https://www.kaggle.com/datasets/smaranjitghose/corn-or-maize-leaf-disease-dataset

model.h5 - https://drive.google.com/file/d/1qJEJY06CpWiK3wf_-Z0K5EMbbZoN0BLe/view?usp=drivesdk

features.npy - https://drive.google.com/file/d/1qJEJY06CpWiK3wf_-Z0K5EMbbZoN0BLe/view?usp=drivesdk

Data Sources
- Disease Classification Images: Collected from agricultural research centers, open-source repositories, and field surveys.


Data Preprocessing:
1. Image Preprocessing:
   - Resizing and normalization of disease classification images.
   - Data augmentation techniques such as rotation, flipping, and color adjustments.
2. Feature Engineering:
   - Extraction of relevant features from the yield and market price datasets.
   - Handling missing values and outliers.
3. Data Splitting:
   - Splitting datasets into training,and test sets.
     

Model Development:
Disease Classification Model
- Architecture: Attentive Convolutional Gated Recurrent Unit (AC-GRU).
- Optimizer: Seeker optimizer.
- Metrics: Accuracy, precision, recall, F1-score, and ROC AUC score.


 Training and Evaluation
- Training: Train models using the training datasets and validate using validation datasets.
- Evaluation Metrics: Evaluate model performance using metrics such as accuracy, MSE and psnr values.
- Model Tuning: Perform hyperparameter tuning to optimize model performance.
  
 Usage
1. Disease Classification:
   - Load and preprocess the image dataset.
   - Train the AC-GRU model using the preprocessed images.
   - Evaluate the model on test images and report metrics.
2. Yield Prediction:
   - Load and preprocess the yield dataset.
   - Train the regression or LSTM model on the yield data.
   - Use the trained model to predict yields based on input parameters.

Future Developments:
1) Increased Diversity: Incorporate a more diverse set of images, including different types crops like sugarcane, wheat and rice . This can be helpful for the cultivators.
2) Mobile Application:  A user-friendly mobile application that can capture images, process them using the trained model, and provide immediate diagnostic results to farmers or agricultural inspectors.
3) Price prediction: With the help of yield prediction we can integrate the price of the yield which will be harvested.

