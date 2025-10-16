# 🧠 Cephalometric Landmark Detection - Ricketts Line AutoDetection

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/ML-Supervised-green)](https://scikit-learn.org/)

This project provides an automated pipeline for detecting key anatomical landmarks—specifically the nasal point (P) and the soft pogonion (Pog’)—in lateral cephalometric radiographs. Using advanced image processing techniques combined with optimization algorithms implemented in Python, the system accurately identifies these critical points and visualizes the Ricketts aesthetic line, a key reference in orthodontic diagnosis and treatment planning. 

By automating the detection and visualization of landmarks, this project aims to streamline orthodontic assessments, minimize human error, and provide a foundation for developing more sophisticated cephalometric analysis tools.

---

## 📌 Project Overview

This project implements an algorithm to automatically detect two key anatomical landmarks — **nasal point (P)** and **soft pogonion (Pog’)** — in cephalometric radiographs.  
Once these points are located, a line is drawn between them to visualize the **Ricketts aesthetic line**, which is commonly used in orthodontic and cephalometric analysis to assess facial profile balance.

The pipeline integrates:
- Image normalization and contrast enhancement  
- Gamma optimization to maximize image contrast  
- Region segmentation and noise reduction  
- Automatic landmark detection  
- Visualization of the Ricketts line

---

## 🛠️ Features

- ✅ Automatic contrast enhancement using CLAHE and gamma correction  
- 📈 Histogram smoothing and thresholding for segmentation  
- 🧭 Automatic localization of nasal and soft pogonion points  
- 🧰 Simple and adaptable Python function structure  
- 🖼️ Real-time line visualization over the image

---

## 🧪 Technologies Used

- [Python](https://www.python.org/)  
- [NumPy](https://numpy.org/)  
- [Matplotlib](https://matplotlib.org/)  
- [scikit-image](https://scikit-image.org/)  
- [scikit-learn](https://scikit-learn.org/stable/)  
- [SciPy](https://scipy.org/)

---

## 🚀 How to Run the Project

You can use this project either in **Google Colab** or your **local environment**.

### 🪐 Option 1: Run on Google Colab
1. Upload the notebook (`.ipynb`) to Colab.  
2. Install the required libraries:
   ```bash
   !pip install pydicom
   ```
3. Run the cells directly — no additional configuration required.

### 💻 Option 2: Run Locally
1. Clone the repository:
  ```bash
  git clone 
  cd 
  ```

2. Install dependencies:
 ```bash
pip install pydicom math numpy pandas scikit-learn opencv-python matplotlib seaborn
```

3. Open the notebook with Jupyter or VS Code and run the cells.

---

## 📥How It Works

1. Image Preprocessing

 - Rescale intensity
 - Enhance contrast with CLAHE
 - Optimize gamma to maximize contrast

2. Segmentation

 - Smooth histogram to find thresholds
 - Crop irrelevant regions

3. Landmark Detection

 - Automatically find nasal and soft pogonion points

4. Visualization

 - Draw the Ricketts line between the detected landmarks

---

## 🖼️ Example Output

| Step             | Visualization                     |
|-----------------|----------------------------------|
| Detected points  | (P and Pog’ marked in red)        |
| Ricketts line    | Red line connecting P and Pog’    |

---

## 📚 **Reference**  

 - Ricketts RM. “Esthetics, environment, and the law of lip relation.” *Am J Orthod.* 1968.  
 - Digital cephalometric analysis in orthodontics.

---

## 📄 Project Author

👨‍💻 Juan Sebastian Peña Valderrama

 - Biomedical Engineer & Artificial Intelligence Specialist. 
 - Radiomics & Imaging Processing Enthusiast.
 - Medical Imaging Analysis Researcher.

📬 Contributions, suggestions, and pull requests are welcome!
