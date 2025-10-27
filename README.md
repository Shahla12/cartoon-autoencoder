# cartoon-autoencoder

Cartoon Autoencoder is a deep learning project that converts real-world images into cartoon-style visuals using a Convolutional Autoencoder (CNN).
The model learns to simplify colors, enhance edges, and produce a clean, stylized cartoon effect automatically — without any manual editing.

### ⚙️ Features

1.Converts real images to smooth cartoon versions
2. CNN-based Autoencoder architecture
3. Color simplification and edge enhancement
4. Works with any custom dataset
5. Model training, testing, and image enhancement pipeline included

### 🧰 Technologies Used

* Python 3.x
* TensorFlow / Keras
* OpenCV
* NumPy, Matplotlib
* Google Colab / vscode

### 🧬 Model Architecture

The project uses a Convolutional Autoencoder, consisting of:
  1. Encoder: Extracts essential features and compresses the image representation.
  2. Decoder: Reconstructs the image in a simplified cartoon style.
  3. Loss Function: Mean Squared Error (MSE) or a combined perceptual loss for smooth texture generation.

### 🧾 Dataset

You can create your own dataset or use a dataset structured as:

```text
cartoon_dataset/
├── train/
│   ├── train_image/       # Original real images
│   └── train_cartoon/     # Corresponding cartoon-style images
└── validation/
    ├── val_image/         # Validation real images
    └── val_cartoon/       # Validation cartoon-style images
text```


### 🚀 **How to Run**

Clone the repository:

```text
git clone https://github.com/<your-username>/cartoon-autoencoder.git
cd cartoon-autoencoder

