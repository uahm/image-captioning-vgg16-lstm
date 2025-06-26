# image-captioning-vgg16-lstm


This project is a deep learning-based **image captioning system** that generates meaningful textual descriptions of images using **VGG16 for image feature extraction** and **LSTM (Long Short-Term Memory) networks** for sequence generation.

---

## 🔍 Overview

- 📸 **Image Feature Extraction** using **VGG16**, a pre-trained CNN from Keras
- 🧾 **Caption Generation** using **LSTM-based sequence modeling**
- 🧠 Trained on image-caption datasets (e.g., Flickr8k/COCO) – customizable
- 💾 Extracted features are stored and reused using `pickle`

---

## 📦 Technologies Used

- Python 3.8+
- TensorFlow / Keras
- NumPy
- VGG16 (from `tensorflow.keras.applications`)
- Pickle (for feature persistence)
- Matplotlib (for visualizations)
- tqdm (for progress bars)

---

## ⚙️ Installation & Setup

1. Clone this repo or download the notebook.

2. Install dependencies:

```bash
pip install tensorflow keras numpy tqdm matplotlib
```

3. Prepare your `Images/` directory and place some images for captioning.

4. Run the notebook: `Project.ipynb`

