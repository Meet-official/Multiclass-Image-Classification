# 🐠 Multiclass-Image Classification with Deep Learning

## 📌 Project Overview

The goal of this project is to **marine images** into distinct categories using **deep learning techniques**. The steps involved in this workflow include:

1. **Training a custom CNN model** designed specifically for this task.
2. **Applying transfer learning** with a range of well-known pre-trained models.
3. **Assessing the performance** of each model and selecting the optimal one.
4. **Saving the best models** for future use in real-time predictions.

---

## 📂 Dataset

* **Type:** A collection of images featuring various species of fish.
* **Categories:**
  1. Fish and seafood: shrimp
  2. Fish and seafood: striped red mullet
  3. Fish and seafood: sea bass
  4. Fish: bass
  5. Fish and seafood: black sea sprat
  6. Fish and seafood: red mullet
  7. Fish and seafood: gilt-head bream
  8. Fish and seafood: red sea bream
  9. Fish: trout
  10. Fish: horse mackerel
* **Image Dimensions:** Images resized to a standard size of 224x224 pixels before training.

---

## 🧠 Models Implemented

| Model              | Type              | Description                          |
| ------------------ | ----------------- | ------------------------------------ |
| **Custom CNN**     | From scratch      | A simple baseline model.             |
| **ResNet50**       | Transfer Learning | Fine-tuned for the fish classification task. |
| **VGG16**          | Transfer Learning | Adapted to the dataset for improved accuracy. |
| **MobileNet**      | Transfer Learning | Best performing model (~99% accuracy). |
| **EfficientNetB0** | Transfer Learning | Good balance between performance and speed. |
| **InceptionV3**    | Transfer Learning | Known for high accuracy and robustness. |

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Deep Learning Framework:** TensorFlow / Keras
* **Data Processing:** NumPy, Pandas
* **Image Manipulation:** OpenCV, Pillow
* **Data Visualization:** Matplotlib, Seaborn
* **Model Format:** `.h5` for storing trained models

---

## 📁 Project Structure


```
📦 fish-classification
│── Multiclass-Fish-Image-classification.ipynb                # Model training script
│── best_model.h5                                             # Saved best model as .h5 file
│── requirements.txt                                          # Python dependencies
│── README.md                                                 # Project documentation
```

---

## 📌 Future Enhancements

* Expand the dataset to include more fish species.
* Implement **data augmentation** techniques for better generalization.
* Develop an **interactive app** to compare multiple models in real-time.
* Optimize models for deployment on **mobile devices**.

---
