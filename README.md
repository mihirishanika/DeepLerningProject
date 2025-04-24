# **Image Captioning System**   

---

## **📌 Project Overview**  
This project implements an **Image Captioning System** using deep learning, where a model generates human-like descriptions for input images. The system combines:  
- **CNN (InceptionV3)** for image feature extraction.  
- **LSTM-based sequence model** for caption generation.  

---

## **🚀 Features**  
✔ **Pre-trained InceptionV3** for efficient image feature extraction.  
✔ **LSTM + Attention-like mechanism** for caption generation.  
✔ **Beam Search** for improved caption quality during inference.  
✔ **BLEU & ROUGE metrics** for quantitative evaluation.  
✔ **Modular code** with data preprocessing, training, and inference pipelines.  

---

## **🛠️ Technical Stack**  
- **Python 3.8+**  
- **TensorFlow 2.x** & **Keras**  
- **NLTK** (for BLEU scoring)  
- **OpenCV/Pillow** (image processing)  
- **Pandas/NumPy** (data handling)  

---

## **📂 Repository Structure**  
```
├── data/                   # Preprocessed data & tokenizer
│   ├── image_features.pkl  # Extracted image features
│   └── tokenizer.pkl       # Trained caption tokenizer
│
├── model/                  # Saved models
│   ├── best_model.keras    # Best trained weights
│   └── training_history.png
│
├── evaluation/             # Metrics & sample results
│   ├── metrics_summary.pkl # BLEU/ROUGE scores
│   └── sample_results.png  # Predicted vs actual captions
│
├── notebooks/              # Jupyter notebooks (EDA, prototyping)
│
├── caption_generator.py    # Main training script
├── inference.py            # Generate captions for new images
├── evaluate.py             # Quantitative evaluation
└── README.md               # This file
```

---

## **🔧 Installation & Setup**  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/your-username/image-captioning.git
   cd image-captioning
   ```

2. **Install dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Download pretrained model (optional):**  
   - Place `best_model.keras` in the `model/` directory.

---

## **🎯 Usage**  

### **1. Training the Model**  
Run the training pipeline:  
```bash
python caption_generator.py
```

### **2. Generating Captions**  
Predict captions for images in `test_images/`:  
```bash
python inference.py
```

### **3. Evaluation**  
Calculate BLEU/ROUGE scores:  
```bash
python evaluate.py
```

---

## **📊 Results**  
| Metric       | Score    |
|--------------|----------|
| **BLEU-1**   | 0.0858   |
| **ROUGE-L**  | 0.3495   |

**Sample Prediction:**  
![WhatsApp Image 2025-04-24 at 13 04 29_46b77065](https://github.com/user-attachments/assets/1aa9e3bb-002f-4439-a48e-b3ead56d0e2e)
![WhatsApp Image 2025-04-24 at 13 04 48_48770088](https://github.com/user-attachments/assets/a3bab1b2-8504-4c5c-8a13-7ff29e0f8702)

  

---

## **📝 Report & Documentation**  
- **Full Report**: [EC9170_Image_Captioning_Report.pdf](2021e012_2021e014.pdf)  
- **Presentation Slides**: [Slides](presentation.pptx)  

---

## **💡 Challenges & Learnings**  
- **Challenge**: Limited GPU resources for training.  
  **Solution**: Used Kaggle notebooks with free GPU quotas.  
- **Learning**: Gained hands-on experience with **sequence-to-sequence models** and **transfer learning**.  
 

---

## **📜 License**  
This project is licensed under **MIT License**.  

---

### **🔗 Connect**  

**Oshada Pramod**  
[![GitHub](https://img.shields.io/badge/GitHub-@oshadapramod-blue)](https://github.com/oshadapramod)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-@oshadapramod-blue)](https://linkedin.com/in/oshadapramod) 

**Mihiri Shanika**  
[![GitHub](https://img.shields.io/badge/GitHub-@mihirishanika-blue)](https://github.com/mihirishanika)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-@mihirishanika-blue)](https://linkedin.com/in/mihirishanika)

---

This README provides a **professional**, **structured**, and **detailed** overview of your project. Customize the placeholder links (e.g., GitHub, report) before publishing! Let me know if you need modifications. 🚀
