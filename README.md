# 🧠 Fake Image Detector using CNN

A deep learning project for binary image classification using Convolutional Neural Networks (CNNs). This model is trained to classify images as either **real** or **fake** using TensorFlow and Keras, with support for Google Colab and Google Drive integration.

---

## 📁 Dataset Structure

The dataset should be organized into training and validation folders, each containing two subfolders: `real` and `fake`.

```

dataset/
├── train/
│   ├── real/
│   └── fake/
└── val/
├── real/
└── fake/

````

> ✅ Note: You can upload a zipped version of this structure and extract it in Google Colab.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
````

### 2. Run on Google Colab

* Mount Google Drive
* Upload or reference your zipped dataset (`data.zip`)
* Follow the Colab cells to:

  * Unzip the data
  * Set paths
  * Train the CNN model
  * Evaluate performance
  * Save/export the model

---

## 🛠️ Tech Stack

* [Python](https://www.python.org/)
* [TensorFlow / Keras](https://www.tensorflow.org/)
* [Google Colab](https://colab.research.google.com/)
* [Matplotlib](https://matplotlib.org/)

---

## 📊 Training Metrics

After training, the script will:

* Display training and validation accuracy
* Plot accuracy and loss graphs
* Output final validation accuracy

---

## 💾 Model Saving

After training:

```python
model.save("fake_image_detector_model.h5")
```

You can later load it using:

```python
from tensorflow.keras.models import load_model
model = load_model("fake_image_detector_model.h5")
```

---

## 🧪 Example Output

| Epoch | Train Accuracy | Validation Accuracy |
| ----- | -------------- | ------------------- |
| 1     | 87.32%         | 84.10%              |
| 2     | 91.45%         | 88.63%              |
| ...   | ...            | ...                 |

---

## 🙌 Acknowledgements

* TensorFlow/Keras documentation
* Google Colab community
* Open image datasets

---

## 📬 Contact

If you found this project helpful or have suggestions:

* 📧 Email: irfan.karimie@gmail.com
* 🌐 GitHub: irfankarim101

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

```

---

Let me know if you'd like:
- A badge section (build status, stars, etc.)
- A Colab badge to launch directly  
- Setup instructions for local environment
```
