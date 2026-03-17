\# 🌸 Flower Classification using CNN \& Transfer Learning (MobileNetV2)



!\[Python](https://img.shields.io/badge/Python-3.x-blue)

!\[TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange)

!\[Keras](https://img.shields.io/badge/Keras-Neural%20Networks-red)

!\[OpenCV](https://img.shields.io/badge/OpenCV-Image%20Processing-green)

!\[Status](https://img.shields.io/badge/Project-Completed-brightgreen)



\## 📌 Project Overview

This project focuses on flower image classification using:

\- CNN from scratch

\- Transfer Learning using MobileNetV2

\- Fine-tuning by unfreezing the last layers



The model is trained on the TensorFlow Flower Dataset to classify flower images into 5 categories.



\---



\## 📂 Dataset

\*\*Dataset:\*\* TensorFlow Flower Dataset



\*\*Classes:\*\*

\- Daisy 🌼

\- Dandelion 🌿

\- Roses 🌹

\- Sunflowers 🌻

\- Tulips 🌷



\---



\## 🧠 Models Used



\### 1. CNN from Scratch

\- Built using Conv2D, MaxPooling, Dense layers

\- Learns features from the beginning

\- Lower validation accuracy compared to TL



\### 2. Transfer Learning using MobileNetV2

\- Uses pretrained ImageNet weights

\- Base model frozen initially

\- Faster convergence and better validation accuracy



\### 3. Fine-Tuning

\- Last layers of MobileNetV2 unfrozen

\- Retrained for 3 epochs

\- Slight performance improvement with some overfitting risk



\---



\## 📊 Results



| Model | Validation Accuracy |

|------|----------------------|

| CNN from Scratch | \~55% |

| Transfer Learning | \~89% |

| Fine-Tuning | Slight improvement |



\---



\## 🔍 Key Observations

\- Transfer Learning converges faster than CNN from scratch

\- TL achieves higher validation accuracy

\- CNN shows slight overfitting

\- Sunflowers are easier to classify

\- Roses are more confusing due to visual similarity with other classes



\---



\## 🖼️ Screenshots



\### Dataset Sample

!\[Dataset Sample](screenshots/dataset\_sample.png)



\### CNN Training Output

!\[CNN Training](screenshots/cnn\_training.png)



\### Transfer Learning Output

!\[Transfer Learning](screenshots/tl\_training.png)



\### Fine-Tuning Output

!\[Fine Tuning](screenshots/fine\_tuning.png)



\### Accuracy Graph

!\[Accuracy Graph](screenshots/accuracy\_plot.png)



\---



\## ⚙️ Technologies Used

\- Python

\- TensorFlow

\- Keras

\- OpenCV

\- Matplotlib

\- Google Colab



\---



\## 🚀 How to Run

1\. Open the notebook in Google Colab or Jupyter Notebook

2\. Install required libraries

3\. Run all cells in sequence

4\. Observe CNN, Transfer Learning, and Fine-Tuning results



\---



\## 📌 Conclusion

Transfer Learning with MobileNetV2 performs much better than CNN from scratch on this dataset. Fine-tuning the last layers can further improve the results slightly, but it also increases overfitting risk.



\---



\## 👩‍💻 Author

\*\*Rachana R\*\*

