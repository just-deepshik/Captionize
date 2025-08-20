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

- 1️⃣ Clone the Repository 
- 2️⃣ Install Dependencies
- 3️⃣ Download Dataset
- 4️⃣ Open the Notebook in Google Colab
- 5️⃣ Run Training & Evaluation
- 6️⃣ Try the Interactive Caption Generator


## 📈 Model Evaluation

The project uses BLEU scores to evaluate the quality of generated captions against reference captions:

- BLEU-1 (unigram precision)

- BLEU-2 (bigram precision)

- BLEU-3 (trigram precision)

- BLEU-4 (4-gram precision)

## 📸 Demo Output
<p align="center">
  <img src="https://github.com/user-attachments/assets/ca1afc50-83b1-442c-a197-c527028d6132" alt="image1" width="250" height="250" />
  <img src="https://github.com/user-attachments/assets/0ee3a74d-39a4-4c32-a7d7-4c1d3055f5ab" alt="image2" width="250" height="250" />
  <img src="https://github.com/user-attachments/assets/1878126d-bd2d-4ef1-83b6-6ddc2fbfb54e" alt="image3" width="250" height="250" />
</p>


⚡ With Captionize, your images don’t just remain images — they tell a story!


