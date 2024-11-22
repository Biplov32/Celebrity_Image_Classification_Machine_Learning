# Celebrity Image Classification Project

This project focuses on classifying celebrity images using machine learning techniques. Below is a summary of the workflow and implementation details.

## Workflow
1. **Image Scraping**
   - Images were scraped using a Python script available in this repository.

2. **Image Preprocessing**
   - OpenCV was used to process the images and select only those with clearly visible faces and two eyes.

3. **Wavelet Transformation**
   - Preprocessed images were subjected to wavelet transformation to enhance feature mapping.

4. **Model Training**
   - Three machine learning models were trained:
     - Support Vector Machine (SVM)
     - Logistic Regression
     - Random Forest
   - GridSearchCV was used to optimize parameters for each model to achieve the best performance.
