# Constellation Classifier

This project focuses on classifying constellations from images using deep learning techniques. Leveraging TensorFlow's Keras library, the project preprocesses images, performs data augmentation, and builds a robust dataset for training and testing a constellation classification model.

## Table of Contents
- [Dataset](#dataset)
- [Key Features](#key-features)
- [Dependencies](#dependencies)
- [Usage](#usage)


---

## Dataset
The dataset consists of images of constellations organized by labels. The project includes steps for:
- Preprocessing raw constellation images.
- Augmenting images to create a richer dataset for training.

### Dataset Details:
- **Source Directory:** `Constellation Dataset/labels`
- **Labels File:** `constellation names.txt`
- **Augmented Data Output:** `augmented_dataset/`

### Configuration Parameters:
- **Image Size:** 256x256 pixels
- **Number of Augmented Images per Class:** 50
- **Batch Size:** 32

---

## Key Features
- **Image Augmentation:** Automatically generates additional images to improve model robustness.
- **TensorFlow Integration:** Uses `ImageDataGenerator` for preprocessing and augmentation.
- **Configurable Paths and Parameters:** Modify image size, batch size, and dataset paths easily.
- **Customizable Pipeline:** Allows flexibility in defining data pipelines and augmentation strategies.

---

## Dependencies
The project requires the following Python libraries:
- `tensorflow` (tested with TensorFlow 2.x)
- `os` (for file handling)

Install dependencies using:
```bash
pip install tensorflow
```

---

## Usage
1. Clone the repository and navigate to the project directory:
   ```bash
   git clone (https://github.com/Basimbaqai/Constellations-Classifier.git)
   cd constellation-classifier
   ```

2. Ensure the dataset is available at the specified paths.

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Constellation\ Classifier.ipynb
   ```

4. Modify parameters in the notebook to suit your dataset and requirements.


---

