# DIAT-Separable-CNN-ECA-HARNet-A-Lightweight-and-Explainable-Model-for-Efficient-HAR

Link to download datasets:

I) HAR dataset 01:(HaiquanChen
chq11;Github aacount): Radar data: Data 1 : https://emailszueducn-my.sharepoint.com/:f:/g/personal/2172281561_email_szu_edu_cn/EpIXC0FHVI9OodwybwiZZtQBSslSMhI2gACWvpNKptUHWA?e=EAWJjg

cite:
  1) Haiquan Chen, Wenbin Ye. Classification of Human Activity Based on Radar Signal Using 1-D Convolutional Neural Network. IEEE Geoscience and Remote Sensing Letters. 2019. DOI: https://doi.org/10.1109/LGRS.2019.2942097
  2) Wenbin Ye, Haiquan Chen, Bing Li. Using an End-to-End Convolutional Network on Radar Signal for Human Activity Classification. IEEE Sensors Journal. 2019, 19 (24), 12244-12252. DOI: https://doi.org/10.1109/JSEN.2019.2938997
  3) ianping Zhu, Haiquan Chen and Wenbin Ye. A Hybrid CNN–LSTM Network for the Classification of Human Activities Based on Micro-Doppler Radar. IEEE Access, vol. 8, pp. 24713-24720, 2020. DOI: https://doi.org/10.1109/ACCESS.2020.2971064

II) DIAT- μ RadHAR dataset:https://ieee-dataport.org/documents/diat-%CE%BCradhar-radar-micro-doppler-signature-dataset-human-suspicious-activity-recognition

pip install tensorflow keras numpy pandas matplotlib

Run the Notebook:

Preprocessing the Data
  1.Load and preprocess the datasets.
  2.Split the datasets into training, validation, and test sets.
  
Train the proposed Model
1. Define the proposed architecture.
2. Compile the model with an appropriate optimizer, loss function, and metrics (e.g., accuracy, precision, recall).
3. Train the model on the training dataset.
4. Use the validation set during training to monitor performance and avoid overfitting.
5. Track metrics such as accuracy, and loss during training.
   
Evaluate the Model
 1. Evaluate the trained model on the test datasets.
 2. Compute and display performance metrics (accuracy, precision, recall, F1 score) for each dataset.
 
Explainable AI Techniques

Feature Maps Visualization:
  
    1. Visualize intermediate feature maps from the CNN layers to understand the learned representations.
    2. Plot the feature maps at different layers to show how the model extracts features at various levels.
    
GradCAM Visualization:

    1. Apply GradCAM (Gradient-weighted Class Activation Mapping) to generate heatmaps for model predictions.
    2. Visualize the importance of different regions of the input image that contributed to the model’s decision.
    3. Overlay the heatmap on the input image to gain insights into the model’s focus during prediction. 

Review Results

 1. Compare the evaluation metrics across all datasets.
 2. Assess the model’s performance and effectiveness.
 3. Review the feature maps and GradCAM results for interpretability of the model’s decision-making process.    
