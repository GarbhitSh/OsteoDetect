# OsteoDetect: Bone Fracture Identification System

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
**OsteoDetect** is a machine learning-based system designed to detect fractures in musculoskeletal radiographs. This project uses the MURA dataset, which includes images of the elbow, hand, and shoulder, and employs state-of-the-art deep learning techniques for image analysis and classification.

## Features
- **Accurate Detection**: Identifies bone fractures in radiographs with high precision.
- **Deep Learning**: Utilizes TensorFlow and Keras for model development.
- **Interactive Interface**: CustomTkinter-based GUI for easy interaction.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/garbhitsh/osteodetect.git
    ```
2. Navigate to the project directory:
    ```bash
    cd osteodetect
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Prepare and preprocess the dataset using the provided scripts.
    ```bash
    python preprocess.py
    ```
2. Train the model on the MURA dataset:
    ```bash
    python train.py
    ```
3. Use the GUI interface to predict fractures:
    ```bash
    python gui.py
    ```

## Dataset
The dataset used in this project is called MURA, which includes 20,335 musculoskeletal radiographs of different bone parts. The dataset is divided into normal and fractured cases as follows:

| **Part**     | **Normal** | **Fractured** | **Total** |
|--------------|:----------:|--------------:|----------:|
| **Elbow**    |    3160    |          2236 |      5396 |
| **Hand**     |    4330    |          1673 |      6003 |
| **Shoulder** |    4496    |          4440 |      8936 |

## Technologies
- **customtkinter** ~= 5.0.3 - For creating a modern, interactive GUI.
- **PyAutoGUI** ~= 0.9.53 - For automating GUI interactions.
- **PyGetWindow** ~= 0.0.9 - For managing window operations.
- **Pillow** ~= 8.4.0 - For image processing.
- **numpy** ~= 1.19.5 - For numerical computations.
- **tensorflow** ~= 2.6.2 - For deep learning model development.
- **keras** ~= 2.6.0 - For neural network implementation.
- **pandas** ~= 1.1.5 - For data manipulation.
- **matplotlib** ~= 3.3.4 - For data visualization.
- **scikit-learn** ~= 0.24.2 - For machine learning algorithms.
- **colorama** ~= 0.4.5 - For colored terminal text output.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for review.

1. Fork the project.
2. Create your feature branch:
    ```bash
    git checkout -b feature/YourFeatureName
    ```
3. Commit your changes:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/YourFeatureName
    ```
5. Open a pull request.

## License
This project is licensed under the MIT License -


