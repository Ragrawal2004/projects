# EMNIST Handwritten Digit Recognition

## Overview

This project utilizes the **EMNIST dataset** to build a deep learning model for handwritten digit recognition using **Convolutional Neural Networks (CNNs)**. The goal is to achieve high accuracy in classifying digits and characters while ensuring an efficient and scalable solution.

## Dataset Details

- **Dataset:** EMNIST (Extended MNIST)
- **Source:** [EMNIST Dataset](https://www.nist.gov/itl/products-and-services/emnist-dataset)
- **Format:** CSV files containing pixel values and labels
- **Classes:** Digits (0-9) and additional character classes
- **Preprocessing:** Normalization, resizing, and augmentation for better model performance

## Installation & Setup

### 1. Clone the Repository

```sh
git clone https://github.com/Ragrawal2004/emnist-handwritten-recognition.git
cd emnist-handwritten-recognition
```

### 2. Install Dependencies

Ensure Python is installed, then install required libraries:

```sh
pip install -r requirements.txt
```

## Model Training & Evaluation

### 1. Data Preprocessing

- Load the dataset
- Normalize pixel values (0-255 → 0-1)
- Split into training & testing sets
- Apply data augmentation for robustness

### 2. Train the Model

Run the training script to train the CNN model:

```sh
python train_model.py
```

### 3. Evaluate the Model

After training, evaluate its accuracy and performance:

```sh
python evaluate_model.py
```

- Generates confusion matrix, accuracy/loss graphs

### 4. Make Predictions

Use the trained model to recognize handwritten digits:

```sh
python predict.py --image path/to/image.png
```

## Results

- Achieved **90% accuracy** on test data
- Used **CNN architecture** for classification
- Performance visualized using graphs and metrics

## Future Enhancements

- Improve accuracy using **advanced augmentation techniques**
- Experiment with **transformer-based models** for better recognition
- Deploy the model as a **web or mobile application**

## Contributing

Contributions are welcome. Follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to your branch (`git push origin feature-branch`)
5. Submit a Pull Request

## License

This project is released under the **MIT License**.

---

**Created by Rounak Agrawal**

