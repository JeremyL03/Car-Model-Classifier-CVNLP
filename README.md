📖 Computer Vision for Car Model Classification
This repository contains the code and resources for a group project on car model classification using computer vision techniques. The goal of this project is to develop a deep learning model that can accurately identify the make and model of a car from an image.

🚀 Project Overview
Goal: Accurately classify car images based on make and model.

Dataset: Stanford Cars Dataset (https://www.kaggle.com/datasets/eduardo4jesus/stanford-cars-dataset)

Models Used:

AlexNet

VGG16 (pre-trained & fine-tuned)

🛠️ Technologies
Python · TensorFlow · Keras · NumPy · Matplotlib · Pandas · Scikit-learn · Seaborn

🔑 Approach
Data Preprocessing

Resizing and normalizing image data.

Organizing data into a suitable structure for model training.

Data Augmentation

Applied techniques like random rotations, shifts, and flips to prevent overfitting and improve model generalization.

Model Training

Experimented with AlexNet and VGG16 architectures.

Utilized transfer learning with pre-trained ImageNet weights on VGG16 to leverage learned features.

Evaluation

Assessed model performance using accuracy and loss on a separate test set.

📊 Results
Model

Accuracy

AlexNet

[Insert AlexNet Accuracy]

VGG16 (fine-tuned)

66.16%

✅ Fine-tuned VGG16 outperformed AlexNet, demonstrating the effectiveness of transfer learning for this specific computer vision task.

📥 How to Run
Open the notebook in Google Colab or a local Jupyter environment.

Upload the Stanford Cars dataset or connect to it via an API.

Run the notebook cells step by step to train and evaluate the models.

📑 Documentation
  📄 Full analysis and results are available in the project report PDF file included in this repository.
