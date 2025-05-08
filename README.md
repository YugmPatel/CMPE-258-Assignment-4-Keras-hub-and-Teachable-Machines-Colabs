# CMPE-258-Assignment-4-Keras-hub-and-Teachable-Machines-Colabs

## **Project Overview**  

This project explores the capabilities of **Google’s Teachable Machine** and **Keras Hub models** by implementing various machine learning examples. The project consists of two main parts:  

1. **Teachable Machine Examples:** Three custom machine learning models trained using Teachable Machine in different domains: **text, image, and video**.  
2. **Keras Hub Implementations:** Variations of Keras Hub models, categorized into **Easy, Intermediate, Advanced, and Expert** levels, implemented for both **image** and **text** tasks in separate Colab notebooks.  

Each implementation will be **executed, explained, and demonstrated** in a YouTube video.  

---  

## **Part A: Teachable Machine Examples**  

We will create and train three models using **Google's Teachable Machine** platform:  

1. **Image Classification**  
   - **Use Case:** Classifying handwritten digits (0-9).  
   - **Dataset:** Handwritten numbers (collected via webcam or images).  
   - **Goal:** Build a model that distinguishes between different digits.  

2. **Text Sentiment Classification**  
   - **Use Case:** Classifying text messages as **positive, negative, or neutral**.  
   - **Dataset:** Custom dataset with sample messages labeled by sentiment.  
   - **Goal:** Train a model to classify new text inputs based on sentiment.  

3. **Video Gesture Recognition**  
   - **Use Case:** Detecting hand gestures (thumbs up, thumbs down, waving).  
   - **Dataset:** Short video clips demonstrating gestures.  
   - **Goal:** Build a model that recognizes different hand gestures in videos.  

Each of these models will be **trained, exported, and embedded into a simple web app for testing**.  

### **Resources for Teachable Machine:**  
- [Teachable Machine GitHub Repository](https://github.com/googlecreativelab/teachablemachine-community)  
- [Awesome Teachable Machine Collection](https://github.com/SashiDo/awesome-teachable-machine)  
- [Teachable Machine Glitch Projects](https://glitch.com/@teachablemachine)  

---  

## **Part B: Keras Hub Implementations (Colab Notebooks)**  

We will modify existing **Keras Hub** models with different levels of complexity. Each model will have a corresponding **Colab notebook** and **a YouTube video explaining the implementation**.  

### **1. Image-Based Models**  
📌 **Easy:**  
- **Model:** MobileNetV2  
- **Task:** Classify objects in images  
- **Modification:** Use a smaller dataset and fine-tune for a specific category  

📌 **Intermediate:**  
- **Model:** ResNet50  
- **Task:** Detect multiple objects in an image  
- **Modification:** Train using a new dataset and adjust hyperparameters  

📌 **Advanced:**  
- **Model:** EfficientNetB7  
- **Task:** Advanced image segmentation  
- **Modification:** Implement additional preprocessing techniques  

📌 **Expert:**  
- **Model:** Vision Transformer (ViT)  
- **Task:** High-accuracy image classification  
- **Modification:** Implement custom training loops with TensorFlow  

### **2. Text-Based Models**  
📌 **Easy:**  
- **Model:** BERT (pre-trained)  
- **Task:** Classify text into categories (e.g., News, Sports, Tech)  
- **Modification:** Fine-tune with a small dataset  

📌 **Intermediate:**  
- **Model:** DistilBERT  
- **Task:** Sentiment analysis  
- **Modification:** Use a different dataset and introduce a new tokenizer  

📌 **Advanced:**  
- **Model:** T5 Transformer  
- **Task:** Text summarization  
- **Modification:** Adjust hyperparameters for improved summaries  

📌 **Expert:**  
- **Model:** GPT-based Model  
- **Task:** Generate conversational responses  
- **Modification:** Implement a retrieval-augmented generation (RAG) system  

## **Installation & Usage**  

### **1. Running the Teachable Machine Models**  
1. Go to [Teachable Machine](https://teachablemachine.withgoogle.com/)  
2. Import the provided datasets  
3. Train the model and export it as a TensorFlow.js model  
4. Deploy it on a simple web app (demo included)  

### **2. Running the Keras Hub Models in Colab**  
1. Open the respective **Colab notebook** from the repository  
2. Run the notebook cells to execute the code  
3. Modify parameters and observe different outputs  
4. Watch the YouTube explanations for detailed guidance  

---

## **Video Demonstrations**  

Each implementation will be explained in a **YouTube video**, where I walk through:  
✅ The **concept** behind the model  
✅ The **code implementation**  
✅ How to **modify** and improve the model  
✅ The **final results and evaluation**  

[🔗 YouTube Playlist (To be updated)](https://youtube.com/)  
