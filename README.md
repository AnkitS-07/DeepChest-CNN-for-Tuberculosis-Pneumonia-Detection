# DeepChest-CNN-for-Tuberculosis-Pneumonia-Detection
DeepChest-CNN: Tuberculosis & Pneumonia Detection from Chest X-rays

Introduction ------------------------------------------------

DeepChest-CNN is a deep learning project that classifies chest X-rays into three categories: Normal, Pneumonia, and Tuberculosis.

The objective is to demonstrate how AI can assist radiologists by automatically detecting lung conditions, speeding up diagnosis, and reducing human error.

Workflow --------------------------------------------------------

Exploratory Data Analysis (EDA)

Data Preprocessing & Augmentation

CNN Model Architecture

Training & Optimization

Model Training

Model Evaluation

Visualized training and validation loss/accuracy curves.

Tested on both single images and batches for practical demonstration.


Project Success -------------------------------------------------------

Class	Precision	Recall	F1-score

Normal	93%	98%	96%

Pneumonia	98%	95%	96%

Tuberculosis	91%	76%	83%


Overall Accuracy: 95%

Validation curves indicate no overfitting.

Confusion matrix shows accurate classification for Normal and Pneumonia, with minor errors for Tuberculosis (due to fewer samples).


Highlights ------------------------------------------------------

Model demonstrates robust learning and generalization.

Can handle single or batch predictions, simulating real clinical use.

Illustrates practical application of CNNs in medical imaging.

