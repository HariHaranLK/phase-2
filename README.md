### **README.md**

---

# 🎤 **Speech Sentiment Analysis Using Deep Learning** 🚀

## 🌟 **Project Overview**
This project performs **speech sentiment analysis** using multiple deep learning models to classify audio data into emotional categories such as **positive, negative, and neutral**. The system processes raw speech signals by converting them into **spectrograms**, which are then fed into various **pre-trained and custom-built deep learning models** for feature extraction and classification.  
<br>  

<div align="center">
  <img src="https://github.com/user-attachments/assets/8a346e7c-83ae-40b7-93f0-d62cedba33cb" width="600" height="300" />
</div>

  

---

## ⚙️ **Technologies Used**
- **🛠️ Programming Language:** Python  
- **📚 Libraries & Frameworks:**  
  - 🐍 **TensorFlow, Keras** – Model training and evaluation  
  - 📊 **NumPy, Pandas** – Data manipulation  
  - 🎵 **Librosa** – Audio processing  
  - 📈 **Matplotlib** – Visualization  
- **🔍 Models Used:**  
  - 🌀 **ResNet-50**  
  - 🚀 **InceptionV3**  
  - 🔥 **VGG16**  
  - ⚡ **DenseNet-121**  
  - ✨ **Xception**  
  - 🎯 **CNN**  
  - 🚦 **EfficientNetB7**  

---

## 🔥 **Workflow**
1. 🎙️ **Data Preprocessing:**  
   - Load raw audio files.  
   - Convert them into **spectrograms** for visual representation.  
   - Normalize and resize the spectrograms for model compatibility.  

2. ⚙️ **Model Training:**  
   - Train multiple models on the spectrogram dataset.  
   - Use **Adam optimizer** with cross-entropy loss.  
   - Apply techniques like **batch normalization and dropout** for stability.  

3. 📊 **Evaluation:**  
   - Validate the models using metrics like **accuracy, loss, precision, and recall**.  
   - Compare performance across different architectures.  
<br> 

---

## 🚀 **Installation**
1. Clone the repository:
```
git clone <your-repo-link>
```
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Run the project:
```
python main.py
```

---

## ✅ **Usage**
- **🔊 Input:** Raw audio files  
- **🎯 Output:** Predicted sentiment labels (**positive, neutral, negative**)  
- **📊 Visualization:** Accuracy and loss graphs  

---

## 📈 **Results**
- **✨ Xception and InceptionV3** demonstrated the highest accuracy, around **97%**, with low loss values.  
- **⚡ CNN and DenseNet-121** provided efficient performance with moderate computational costs.  
- **🔥 VGG16 and ResNet-50** showed slight overfitting but maintained high accuracy.  
<br>  
![image](https://github.com/user-attachments/assets/c22ed786-8b63-4de2-ace1-08057b143422)  

---

## 🚀 **Future Enhancements**
- 🛠️ **Real-time Speech Sentiment Analysis:** Implementing live audio input for real-time classification.  
- 🔗 **Integration with Speech-to-Text:** Combining sentiment and content analysis for richer insights.  
- 📊 **Fine-Tuning Models:** Using larger and more diverse datasets to improve generalization.  

---

## 👥 **Contributors**
- 🧑‍💻 **HARI HARAN L K**  
- 🧑‍🎓 **KANNAN G**  
- 🧑‍🎓 **SANJAY A**  
<br>  
![Teamwork](https://media.giphy.com/media/l3q2z2e5u7duuh1H2/giphy.gif)  

---

## 📜 **License**
This project is licensed under the **MIT License**.  
<br>  
![License](https://media.giphy.com/media/l0HlQ7LRalNBSuLzq/giphy.gif)  

---

✅ Let me know if you need any more tweaks or additions! 🚀
