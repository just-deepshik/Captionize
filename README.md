# Captionize 🖼️✨  
**Automatic Image Caption Generator with Attention**

👉 [Download Project files](https://drive.google.com/drive/folders/1fZSiGbpB1SXEmW6Pkd6ueNmYPeFjeiLh?usp=sharing) 

## 📌 Project Description  
**Captionize** is a deep learning project that generates captions for images automatically. It combines **Computer Vision (CNN)** and **Natural Language Processing (RNN + Attention)** to describe what is in an image using natural language.

The workflow includes:  
- Extracting features from images using **InceptionV3 (CNN)**  
- Modeling caption sequences with **LSTM + Bahdanau Attention**  
- Evaluating caption generation with **BLEU scores**  
- An **interactive interface** in Google Colab for uploading an image and generating captions with a user-friendly UI.  
---



## 📊 Dataset  
This project uses **Flickr8k dataset** containing images and captions.  

👉 [Download Dataset](https://www.kaggle.com/datasets/adityajn105/flickr8k)  


## 🚀 Steps to Run the Project  

- 1️⃣ Download the project files and dataset from the links provided above
- 2️⃣ Open the Notebook in Google Colab
- 3️⃣ Run Training & Evaluation
- 4️⃣ Try the Interactive Caption Generator


## 📈 Model Evaluation

The project uses BLEU scores to evaluate the quality of generated captions against reference captions:

- BLEU-1 (unigram precision)

- BLEU-2 (bigram precision)

- BLEU-3 (trigram precision)

- BLEU-4 (4-gram precision)

## 📸 Demo Output
<p align="center">
  <img src="https://github.com/user-attachments/assets/5104d50f-a86f-4458-8482-23cb22031bd8" alt="Screenshot 1" width="300" height="300" />
  <img src="https://github.com/user-attachments/assets/6d67a3d0-b2ff-4dfc-8f14-c9957a4b8006" alt="Screenshot 2" width="300" height="300" />
  <img src="https://github.com/user-attachments/assets/86ebac09-373d-4808-a8f7-2849a8a379e3" alt="Screenshot 3" width="300" height="300" />
</p>

⚡ With Captionize, your images don’t just remain images — they tell a story!


