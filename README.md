# Handwritten Alphabets and Digits Recognition

## Description
This project focuses on developing Convolutional Neural Network (CNN) models to accurately recognize handwritten alphabets (A-Z) and digits (0-9). Two distinct datasets are utilized to train and evaluate the models, ensuring high accuracy in character recognition tasks. The project showcases deep learning techniques to classify grayscale images of handwritten characters.

## Datasets Used
### 1. **Handwritten Alphabets Dataset**  
   - **Source**: AZ Handwritten Alphabets Dataset (in CSV format).  
   - **Content**:  
     - Contains 26 categories (A-Z), each consisting of grayscale images of handwritten alphabets.  
     - Each image is centred in a box of 28x28 pixels.  
   - **Note**: A script is provided to convert the CSV data into actual images in `.png` format.  

### 2. **Handwritten Digits Dataset**  
   - **Source**: MNIST Digit Recognizer Dataset.  
   - **Content**:  
     - Includes 10 categories (0-9), with grayscale images of handwritten digits.  
     - Images are 28x28 pixels in size.  
   - **Note**: A script is provided to convert the CSV data into actual images in `.png` format.

## How to Use
### 1. **Access the Datasets**  
   - Handwritten Alphabets Dataset: Available on Kaggle [AZ Handwritten Alphabets](https://www.kaggle.com/).  
   - Handwritten Digits Dataset: Available on Kaggle [MNIST Dataset](https://www.kaggle.com/c/digit-recognizer).

### 2. **Convert CSV to Images**  
   - Both datasets are initially in CSV format.  
   - Use the provided script, **`Kernel CSV To Images`**, to generate `.png` images from the CSV files. This step is essential for preprocessing the data before training CNN models.  

### 3. **Build CNN Models**  
   - Frameworks: The models can be built and trained using **TensorFlow** or **PyTorch**.  
   - Process:  
     - Preprocess the images (normalization, reshaping, etc.).  
     - Design CNN architecture (convolutional layers, pooling layers, and dense layers).  
     - Train the models using the alphabet and digit datasets.  
     - Evaluate the models' accuracy on validation and test datasets.  

## Project Features
- **Handwritten Alphabets Recognition**: Classifies grayscale images of alphabets (A-Z) with high accuracy.  
- **Handwritten Digits Recognition**: Accurately identifies handwritten digits (0-9) using the MNIST dataset.  
- **End-to-End Pipeline**: Includes dataset preprocessing, CNN model building, training, and evaluation.  

## Results
- Achieved over **95% accuracy** on the MNIST digit recognition task.  
- Successfully classified handwritten alphabets with high precision using the AZ dataset.  

## Technologies Used
- **Languages**: Python  
- **Libraries**: TensorFlow, Keras, NumPy, Pandas, Matplotlib  
- **Tools**: Jupyter Notebook  

## Future Enhancements
- Add data augmentation to improve model generalization.  
- Experiment with advanced architectures like ResNet or VGGNet for better accuracy.  
- Develop a web application for real-time handwritten character recognition.

