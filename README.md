# Handwriting Recognition using Transfer Learning

## Project Overview
This project focuses on enhancing handwriting recognition by leveraging **Transfer Learning**. The goal is to build a model that first learns to recognize hand-drawn shapes and then transfers this knowledge to recognize handwritten alphanumeric characters. The approach reduces computational costs and training time by reusing feature extraction learned from the shapes dataset. The final model can be extended for Optical Character Recognition (OCR) tasks.

### Key Features:
- **Shape Recognition**: The model is first trained on a custom dataset of hand-drawn shapes (e.g., circles, triangles, squares, grids, and infinity symbols).
- **Transfer Learning**: The knowledge from the shapes model is transferred to recognize handwritten digits from the MNIST dataset.
- **Efficient Training**: By freezing the convolutional layers, only the final classification layer is trained for the new task, reducing training time.
- **High Accuracy**: The model achieves an accuracy of **82%** on the MNIST dataset, with faster training compared to training from scratch.

## Technologies Used
- **Programming Language**: Python
- **Libraries/Frameworks**:
  - TensorFlow
  - Keras
  - NumPy
  - Pandas
- **IDE**: Google Colab
- **Datasets**:
  - Custom hand-drawn shapes dataset
  - MNIST dataset (for handwritten digits)

## Installation and Setup

### Prerequisites
Before running the project, ensure you have the following installed:
- **Python 3.7 or higher**
- **TensorFlow 2.x**
- **Keras**
- **NumPy**
- **Pandas**

### Step 1: Clone the Repository
Clone the repository to your local machine:
```bash
git clone https://github.com/your-username/handwriting-recognition-transfer-learning.git
