
# Retinal Diseases Classification using Deep Learning

This project aims to classify retinal diseases using deep learning techniques. By leveraging convolutional neural networks (CNNs), we can analyze retinal images and accurately identify various retinal conditions.
 

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Tech Stack](#techStack)
- [Installation](#installation)
- [Model Architecture](#model-architecture)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Execution Video](#executionVideo)
- [Reference Papers](#referencePapers)
- [Documentation](#documentation)
- [Acknowledgements](#acknowledgements)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Retinal diseases such as diabetic retinopathy, glaucoma, and age-related macular degeneration are leading causes of vision impairment and blindness. Early detection and accurate classification of these diseases are crucial for effective treatment and prevention of vision loss. This project utilizes deep learning models to automate the classification of retinal images into different disease categories.


## Features

- **Automated classification** of retinal images into different disease categories.
- **Preprocessing techniques** to enhance image quality and highlight relevant features.
- **Convolutional Neural Network (CNN)** architecture optimized for retinal image analysis.
- **Performance metrics** including accuracy, precision, recall, and F1-score for model evaluation.


## Dataset

The dataset used in this project consists of retinal images annotated with corresponding disease labels. The images are sourced from publicly available medical image repositories and research datasets. The dataset is split into training, validation, and test sets for model development and evaluation.

## Tech Stack

- Python 3.x
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- scikit-learn
- sqlite3
- tkinter
## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/Retinal-Disease-Classification.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Retinal-Disease-Classification
    ```
3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Model Architecture

![Model Architecture](https://drive.google.com/uc?id=1etA3__6MJ4GaZYuqvAWYoipCPmBPsRNx "Model Architecture")

## Usage

1. **Data Preparation**: Ensure that your dataset is organized in the appropriate directory structure.

2. **Model Training**: Train the model using the training dataset by running the training script:
    ```sh
    python train.py
    ```
3. **Model Evaluation**: Evaluate the trained model
```sh
python evaluate.py
 ```

4.  **Prediction** : Use the trained model to make predictions on new retinal images:

```sh
python predict.py --image_path path/to/image.jpg
```
## Screenshots

![Main GUI](https://drive.google.com/uc?id=1JAHr6-NtJRCPP4ibxVso1dtZeUPy_ouc "Main GUI")

![Registration Page](https://drive.google.com/uc?id=1cRNYV8MwElizX3CfTt3XImM1o2w0oe6w "Registration Page")

![Authentication](https://drive.google.com/uc?id=1IIND5XUgSUtkq7dq1cMHo85u6azH1B-K "Authentication")

![Login Page](https://drive.google.com/uc?id=173Xc9mNFG_py_pXMdLjOS8ltAJQBO3qV "Login Page")

![Home Dashboard](https://drive.google.com/uc?id=1ua6RoT5i_WV0niF2fNM4vzb_51q_tuSr "Home Dashboard")

![Normal Image](https://drive.google.com/uc?id=1DfLijB8epuc1GtVNXHW4m3lWzlA1IwtS "Normal Image")

![High Myopia](https://drive.google.com/uc?id=1a_KQ9sDNVLkrS4liyj5flG42SBhIPFo7 "High Myopia")

![Pathological Myopia](https://drive.google.com/uc?id=1cxN7kcksvwxd2cDyECc9Phe9jtAdoUmV "Pathological Myopia")

![Model Accuracy](https://drive.google.com/uc?id=1C_XGZ2z5D4lX40WuZHwvkShZlwK9paCH "Model Accuracy")


## Execution Video

Watch a demonstration of the project execution:
- [Project Execution Video](https://drive.google.com/file/d/1FkRnN6I8BO9MM8KPGdHopTUTICax7aUh/view?usp=sharing)

## Reference Papers

- [Multi-Label Retinal Disease Classification Using Transformers](https://drive.google.com/file/d/17Gy65W0qZaicrA9_o6XcK0g1M5TUFLZL/view?usp=sharing)
- [Automated Classification of Retinal Diseases in STARE Database Using Neural Network Approach](https://drive.google.com/file/d/1V4JbTkvv1Q1ko_U94vnhqlMMmb0XrPrY/view?usp=sharing)
- [General Multi-label Image Classification with Transformers](https://drive.google.com/file/d/10sEdOTCf0t3yU79SBp7sWGUT8WFhILhm/view?usp=drive_link)
## Documentation

For detailed documentation on retinal diseases and the methodology used in this project, please refer to our published paper:

- [Published Paper on Retinal Disease Classification](https://drive.google.com/file/d/1R4G2zCliynYsNzGiDj2f2YEr4lQRUvTD/view?usp=sharing)

This paper discusses the research, methodology, and results related to the classification of retinal diseases using deep learning techniques.

## Acknowledgements

- The dataset providers and contributors to the field of retinal imaging and analysis.
- The open-source community for providing valuable tools and libraries.
- All researchers and developers who have contributed to advancing deep learning techniques for medical image analysis.





## Contributing

Guidelines for contributing to the project. Include information on how to:
- Report issues
- Submit changes via pull requests
- Code style guide if applicable


## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Umakant13/Retinal-Disease-Classification-using-Deep-Learning/blob/main/LICENSE) file for more details.


