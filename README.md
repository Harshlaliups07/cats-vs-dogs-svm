# 🐱🐶 Cats vs Dogs Image Classification using SVM

This project is part of my internship at **Credora** (ML Task 03), where we build a Support Vector Machine (SVM) based classifier to differentiate between images of cats and dogs using the Kaggle dataset.

---

## 📁 Dataset

- Dataset used: [Kaggle - Dogs vs Cats](https://www.kaggle.com/competitions/dogs-vs-cats/data)
- Contains 25,000 labeled images of cats and dogs (training set)

---

## ⚙️ Technologies & Libraries Used

- Python
- Scikit-learn
- OpenCV / PIL for image processing
- NumPy
- Matplotlib
- Google Colab

---

## 🧠 Methodology

1. Load and preprocess image dataset (resize to 64x64, convert to grayscale/RGB)
2. Convert images to feature vectors
3. Label encoding for "cat" and "dog"
4. Train a Support Vector Machine (SVM) model
5. Evaluate using accuracy, confusion matrix

---

## 🚀 How to Run

1. Upload the dataset or unzip it in Colab
2. Run the Google Colab notebook cells sequentially
3. The final trained SVM model will give predictions on unseen images

---

## 📊 Results

- Accuracy: ~85% (depends on preprocessing and number of images)
- Confusion matrix shows how well the model distinguishes cats from dogs

---

## 👩‍💻 Author

**Harshali Upase**  
Email: harshaliupase12@gmail.com

---

## 📌 Note

- For better performance, feature extraction (like HOG) and dimensionality reduction (PCA) can be added.
- SVMs are slower on large image datasets; CNNs are usually more optimal for image tasks.
 



