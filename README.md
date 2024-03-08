# 🐶🐱 Dog & Cat Classification Project 🖼️

## Description
The Dog & Cat Classification project is a machine learning endeavor aimed at accurately classifying images of dogs and cats using convolutional neural networks (CNNs). Leveraging a dataset containing labeled images of these furry friends, the project demonstrates the prowess of CNNs in image classification tasks.

## Accuracy and Loss 📊
The trained model boasts an impressive accuracy of 99.21% with a loss of 0.229, showcasing its proficiency in distinguishing between images of dogs and cats.

## Libraries Used 📚
The project harnesses the following Python libraries:
- TensorFlow 🧠
- Keras 🤖
- NumPy 🔢
- Matplotlib 📊
- Pandas (for data analysis, if applicable) 🐼

## Requirements 🛠️
To run the Dog & Cat Classification project, you'll need to install the following libraries:

```bash
pip install keras
pip install numpy
pip install pandas
```
In addition, you'll need to import the necessary TensorFlow Keras layers:

```bash
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Conv2D, MaxPooling2D, Flatten, Dense
```

## Dataset 📸

To use the dataset for the Dog & Cat Classification project, follow these steps:

1. Access the following link to download the dataset: [Dataset Download Link](Dataset_Download_Link)

2. Once downloaded, extract the contents of the ZIP file to your desired location on your local machine.

3. Ensure that the extracted dataset folder is accessible and located in the appropriate directory specified in your code.

4. Use the following code snippet to extract the dataset programmatically:

```python
from zipfile import ZipFile
file_name = "/content/drive/My Drive/dataset_new.zip"

# Extract the contents of the ZIP file
with ZipFile(file_name, 'r') as zip_ref:
    zip_ref.extractall("/desired/extract/location")
```

