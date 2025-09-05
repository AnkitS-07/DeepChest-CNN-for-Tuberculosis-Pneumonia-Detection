# DeepChest-CNN-for-Tuberculosis-Pneumonia-Detection

🩺 DeepChest-CNN: Automated Tuberculosis & Pneumonia Detection

🌟 Introduction :-

DeepChest is an AI-powered Convolutional Neural Network (CNN) designed to analyze chest X-rays and automatically classify patients into Normal, Pneumonia, or Tuberculosis categories.
By leveraging deep learning, DeepChest aims to support radiologists, reduce diagnostic time, and provide reliable preliminary screening for chest diseases.

⚡ Key Features :-

1) High Accuracy: Classifies chest X-rays with ~95–96% overall accuracy.

2) Single & Batch Predictions: Predict for one image or multiple images simultaneously.

3) Advanced CNN Architecture: Convolutional layers, ReLU activation, MaxPooling, and fully connected layers optimized for medical imaging.

4) Data Augmentation & Preprocessing: Handles class imbalance and improves generalization with flips, rotations, normalization, and resizing.

5) Evaluation Metrics: Provides classification reports, confusion matrices, and visualizations.

6) User-Friendly: Easy for doctors and researchers to upload X-rays and get instant predictions.
   

🚀 Workflow :-

- Dataset Exploration (EDA):

Check class distributions, sample quality, and balance.

Visualize sample chest X-rays.

- Preprocessing & Augmentation:

Resize images to 224×224.

Normalize pixel values.

Apply random flips and rotations.

- Model Training:

CNN trained using PyTorch.

Optimized with Adam and CrossEntropyLoss.

5 epochs of training with validation for generalization.

- Model Evaluation:

Loss & accuracy curves, confusion matrix, and classification report.

- Predictions:

Single image prediction for clinical use.

Batch predictions for dataset validation.


🏆 Success & Achievements :-

 -> High Accuracy: Achieved 95–96% overall accuracy.

 -> Reliable Detection: Strong performance on Normal and Pneumonia classes; moderate improvement needed for Tuberculosis.

 -> Clinical Simulation Ready: Successfully predicts single X-rays, simulating real-world usage for doctors.

 -> Visual Reporting: Provides intuitive loss/accuracy graphs and confusion matrix for model interpretability.


💡 Future Improvements :-

 + Expand Tuberculosis Dataset: Improve precision and recall for TB classification.

 + Integration with Hospital Systems: Real-time deployment in radiology departments.

 + Multi-Disease Detection: Extend to other chest conditions like COVID-19, lung cancer, or fibrosis.

 + Explainable AI (XAI): Highlight regions of interest in X-rays to provide visual explanations.


🌐 Scalability :-

 => Cross-Hospital Deployment: Compatible with multiple hospital imaging systems.

 => Cloud-Based Inference: Deploy on cloud servers for real-time predictions.

 => Multi-User Access: Multiple doctors can simultaneously upload and predict X-rays.

 => Future Expansion: Supports adding new disease classes or imaging modalities (CT scans, MRI).
