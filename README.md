# 🧠 Synthetic Medical Image Generation using GAN

## 📌 Overview
This project addresses the problem of limited medical imaging data by using Generative Adversarial Networks (GANs) to generate realistic synthetic images.

Medical datasets are often small, expensive, and restricted due to privacy. This project uses a Deep Convolutional GAN (DCGAN) to learn patterns from real medical images and generate synthetic samples to improve model performance.

---

## 🎯 Objectives
- Generate realistic synthetic medical images
- Augment limited datasets
- Improve classification accuracy
- Understand GAN training dynamics

---

## 🧠 What is GAN?
A Generative Adversarial Network (GAN) consists of two models:

- Generator: Creates fake images from random noise
- Discriminator: Distinguishes between real and fake images

Both models are trained together in a competitive setting.

---

## 🏥 Use Cases
- Chest X-ray (Pneumonia / COVID detection)
- Brain MRI (Tumor detection)
- CT scan image enhancement

---

## ⚙️ Tech Stack
- Python
- PyTorch
- NumPy
- OpenCV
- Matplotlib

---

## 📂 Dataset
Example datasets:
- Chest X-ray dataset (Kaggle)
- Brain MRI dataset

Images are resized to 128x128 and normalized before training.

---

## 🛠️ Project Structure
medical-gan/
│── data/
│── models/
│── outputs/
│── train.py
│── generator.py
│── discriminator.py
│── utils.py
│── README.md

---

## 🚀 How to Run

### 1. Clone the repository
git clone https://github.com/your-username/medical-gan.git  
cd medical-gan  

### 2. Install dependencies
pip install torch torchvision matplotlib numpy opencv-python  

### 3. Run training
python train.py  

---

## 🧪 Results
- Generated realistic synthetic medical images  
- Increased dataset size  
- Improved model performance after augmentation  

---

## 📊 Evaluation Metrics
- FID Score (Fréchet Inception Distance)
- SSIM (Structural Similarity Index)

---

## ⚠️ Challenges
- GAN training instability  
- Mode collapse  
- Data quality dependency  

---

## 🔥 Future Improvements
- Implement CycleGAN for MRI ↔ CT conversion  
- Use StyleGAN for higher quality images  
- Deploy using Flask or React  

---

## 💼 Applications
- Healthcare AI systems  
- Medical research  
- Diagnostic support systems  

---

## ⚖️ Ethical Considerations
- Synthetic data should not replace real diagnosis  
- Ensure responsible and ethical use  
- Maintain data privacy  

---

## 👨‍💻 Author
Harsh Chaturvedi  
BTech AI Student  

---

## 📌 License
This project is for educational and research purposes only.
