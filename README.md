# Image Classification: Animals (Cats, Dogs, and Foxes)

A deep learning project to classify animal images using PyTorch and Keras. This project uses a dataset of Cats, Dogs, and Foxes to train a Convolutional Neural Network (CNN).

## 🚀 Features
- **Dataset Integration**: Automatically downloads the dataset from Kaggle using `kagglehub`.
- **Model Architecture**: Custom CNN implementation in PyTorch.
- **Preprocessing**: Robust image preprocessing and augmentation.
- **Inference**: Prediction script for individual images.

## 🛠️ Tech Stack
- **Languages**: Python
- **Libraries**: 
  - PyTorch
  - TensorFlow / Keras (for inference)
  - Torchvision
  - Matplotlib
  - NumPy

## 📂 Project Structure
- `Image_Classification.ipynb`: Main notebook containing data loading, training, and evaluation logic.
- `animal_classifier.pth`: Trained model weights (generated after training).

## 📊 Dataset
The project uses the [Animal Image Dataset (Cats, Dogs, and Foxes)](https://www.kaggle.com/datasets/snmahsa/animal-image-dataset-cats-dogs-and-foxes) from Kaggle.

## 📝 Usage
1. Open the `.ipynb` file in Google Colab or a local Jupyter environment.
2. Ensure you have the required dependencies installed:
   ```bash
   pip install torch torchvision tensorflow kagglehub matplotlib numpy
   ```
3. Run the cells sequentially to download the data and train the model.

---
*Created by VastSea0*
