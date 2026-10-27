# Image Classification: Cats, Dogs and Foxes

A small convolutional neural network in PyTorch that sorts animal photos into three classes: cat, dog and fox. Written as a learning project.

## Dataset

[Animal Image Dataset (Cats, Dogs, and Foxes)](https://www.kaggle.com/datasets/snmahsa/animal-image-dataset-cats-dogs-and-foxes) on Kaggle. The notebook downloads it with `kagglehub`, so you don't need to fetch it by hand.

## Running it

Open [`Image_Classification.ipynb`](Image_Classification.ipynb) in Google Colab or Jupyter and run the cells from the top. Locally, install the dependencies first:

```sh
pip install torch torchvision kagglehub matplotlib numpy
```

The notebook:

1. Downloads the dataset.
2. Resizes and normalizes the images and loads them with `ImageFolder`.
3. Trains the CNN and plots the loss.
4. Saves the weights to `animal_classifier.pth`. Weights are not committed.

## Known issue

The last cell, which predicts a single image, loads the model with TensorFlow/Keras (`load_model`). That can't read PyTorch weights. Prediction should use `torch.load` and the same transforms as training. A pull request that fixes this is welcome.

## License

[GPL-3.0](LICENSE). Part of [YouthX Research](https://github.com/YouthX-Research).
