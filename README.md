# Transfer Learning with Pre-trained ResNet18

This repository contains a Google Colab implementation of **transfer learning** using a **pre-trained ResNet18** model on the **UEH-VDR (Vietnamese Dish Recognition)** dataset.  
It demonstrates how to fine-tune existing deep learning models for new image classification tasks efficiently.

---

## Features

- **Pre-trained ResNet18**: Loaded from PyTorch torchvision models.
- **Fine-tuning**: Modified the final fully connected layer to fit the new dataset classes.
- **Data Augmentation**: Applied random transforms to improve model generalization.
- **Efficient Training**: Used GPU acceleration in Google Colab for faster training.
- **Visualization**: Displayed predictions on sample test images.

---

## Dataset

The dataset used for this project:

**UEH-VDR (Vietnamese Dish Recognition Dataset)**  
[Kaggle Link](https://www.kaggle.com/datasets/truthtaicom/uehvdr-dataset)

Please download the dataset and upload it to your Google Drive to access it in Colab.

---

## Requirements

The notebook is designed to run on **Google Colab**.  
No local setup required — however, if you want to run it locally, you will need:

- Python 3.7+
- PyTorch
- torchvision
- matplotlib
- numpy

You can install them with:

```bash
pip install torch torchvision matplotlib num
