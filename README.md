# IMAGE-CLASSIFICATION-WEB-APP

---

## 🌼 Image Classification Web Application using CNN

This project focuses on building a web-based image classification system using deep learning to automatically identify and categorize images of flowers. The aim was to create a responsive and accurate model capable of assisting in real-world visual recognition tasks.

The task was to develop a Python-based web application that could take an image of a flower as input and accurately classify it into one of five categories: **Daisy, Dandelion, Rose, Sunflower, or Tulip**. For training the model, the publicly available **‘Flower Photos’ dataset from TensorFlow** was used, containing a total of **3,670 labeled images** across these five classes.
**Dataset source**: [https://storage.googleapis.com/download.tensorflow.org/example\_images/flower\_photos.tgz](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz)

The model was built using a **Convolutional Neural Network (CNN)** implemented with **TensorFlow** and **Keras**. Image preprocessing steps included resizing, grayscale conversion, reflection, Gaussian blurring, histogram equalization, rotation, and translation to improve feature learning. The architecture included three convolutional blocks, each followed by max pooling layers, a dense hidden layer of 128 units, and a final output layer with softmax activation to classify into five categories.

The dataset was split into **80% for training and 20% for validation**, and the model was trained over **10 epochs**, reaching a high accuracy of **99.18%**. The trained model was saved in `.h5` format and integrated into a **Gradio-powered web interface**, allowing real-time user interaction through image upload and classification.

### Additional Highlights & Project Impact

* **Interactive UI with Gradio**: Users can access the model in a simple web interface without needing any coding knowledge.
* **High Accuracy with Minimal Resources**: The project demonstrates how deep learning models can achieve high performance even with limited computational resources (Intel i5, 8GB RAM).
* **Educational Value**: This project serves as a hands-on example for understanding end-to-end machine learning pipelines, from data preprocessing to deployment.
* **Future Scope**: The system can be expanded to classify more flower species, or be adapted to other domains like medical image diagnosis, plant disease detection, or wildlife monitoring.
* **Open Source Potential**: Since it uses open-source tools and a public dataset, this project can be replicated or extended by students, developers, or researchers.

---


