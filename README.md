### **README.md**

---

# **Speech Sentiment Analysis Using Deep Learning**

## **Project Overview**
This project performs **speech sentiment analysis** using multiple deep learning models to classify audio data into different emotional categories such as **positive, negative, and neutral**. The system processes raw speech signals by converting them into **spectrograms**, which are fed into various pre-trained and custom-built deep learning models for feature extraction and classification.  

---

## **Technologies Used**
- **Programming Language:** Python  
- **Libraries & Frameworks:**  
  - TensorFlow, Keras – Model training and evaluation  
  - NumPy, Pandas – Data manipulation  
  - Librosa – Audio processing  
  - Matplotlib – Visualization  
- **Models Used:**  
  - ResNet-50  
  - InceptionV3  
  - VGG16  
  - DenseNet-121  
  - Xception  
  - CNN  
  - EfficientNetB7  

---

## **Workflow**
1. **Data Preprocessing:**  
   - Load raw audio files.  
   - Convert them into **spectrograms** for visual representation.  
   - Normalize and resize the spectrograms for model compatibility.  

2. **Model Training:**  
   - Train multiple models on the spectrogram dataset.  
   - Use **Adam optimizer** with cross-entropy loss.  
   - Apply techniques like **batch normalization and dropout** for stability.  

3. **Evaluation:**  
   - Validate the models using metrics like **accuracy, loss, precision, and recall**.  
   - Compare performance across different architectures.  

---

## **Installation**
1. Clone the repository:
```
git clone <your-repo-link>
```

---

## **Usage**
- **Input:** Raw audio files  
- **Output:** Predicted sentiment labels (positive, neutral, negative)  
- **Visualization:** Accuracy and loss graphs  

---

## **Results**
- **Xception and InceptionV3** demonstrated the highest accuracy, around **97%**, with low loss values.  
- **CNN and DenseNet-121** provided efficient performance with moderate computational costs.  
- **VGG16 and ResNet-50** showed slight overfitting but maintained high accuracy.  

![image](https://github.com/user-attachments/assets/d66e0bc4-33d0-40a7-8192-3a1e637b9e5d)

---

## **Future Enhancements**
- Real-time speech sentiment analysis using live audio input.  
- Integration with **speech-to-text systems** for combined sentiment and content analysis.  
- Fine-tuning models with larger and more diverse datasets.  

---

## **Contributors**
- HARI HARAN L K
- KANNAN G, SANJAY A

---

## **License**
This project is licensed under the **MIT License**.
