# Cat vs. Dog Image Classification

This project demonstrates binary image classification using a Convolutional Neural Network (CNN). The goal is to accurately distinguish between images of cats and dogs.

The problem is tackled using two distinct approaches:
1.  A custom CNN model built from scratch.
2.  Transfer Learning using a pre-trained model.

The performance and characteristics of these two methods are then compared and analyzed.

## 💾 Dataset

This project uses the **Microsoft Cats vs. Dogs Dataset**, which is available on Kaggle. It contains a large collection of 25,000 JPG images of cats and dogs.

- **Source:** [Kaggle - Microsoft Cats vs. Dogs Dataset](https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset)
- **Content:** The dataset includes 12,500 images of cats and 12,500 images of dogs.
- **Structure:** The original data is provided in a `PetImages` folder, with `Cat` and `Dog` subdirectories. As part of this project's data preparation pipeline, these images are organized into `train` and `validation` sets and cleaned to remove any corrupted or non-image files.