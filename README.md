# Exoplanet-atmospheric-characterization-1

# 🌌 Exoplanet Classification using Machine Learning

This project was developed as part of the GSoC 2025 Test Task for the ML4SCI (Machine Learning for Science) organization. The goal is to build a machine learning pipeline to classify exoplanets based on their light curve image data using supervised learning techniques.

## 📌 Project Objective

To explore, build, and evaluate an efficient ML model that can accurately classify whether a given celestial body is an exoplanet or not, using image-based data derived from light curves.

## 🛠️ Tools & Technologies Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- TensorFlow / Keras
- Scikit-learn
- Google Colab

## 📂 Project Structure as follows

## 🚀 Steps Performed

1. **Data Preparation**: 
   - Converted light curve CSVs into grayscale image data.
   - Stored images in a local folder for manual upload.

2. **Image Preprocessing**:
   - Resized images, normalized pixel values, and converted to NumPy arrays.

3. **Model Building**:
   - Used Convolutional Neural Networks (CNNs) for classification.
   - Achieved a satisfactory training and validation accuracy.

4. **Model Saving**:
   - Trained model saved as `model.h5` for reuse and deployment.

5. **Report Generation**:
   - Includes insights, challenges, learnings, and future scope.

## 📊 Results

- Achieved high accuracy on the validation dataset.
- Demonstrated effective use of image-based ML in scientific tasks.

## 🧠 What I Learned

- Converting CSV-based signal data to image form.
- Building and training CNNs on image datasets.
- Handling limited data using augmentation techniques.
- Structuring and documenting ML projects.

## 🤝 Contributions

If accepted, I look forward to contributing further to the ML4SCI initiative by refining this pipeline and extending it to more complex datasets.

---
