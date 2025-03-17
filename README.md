# Real-Time Traffic Sign Recognition

## Project Overview
The **Real-Time Traffic Sign Recognition** project aims to develop a system that can instantly identify and interpret traffic signs. The application enhances road safety by providing drivers with immediate recognition and understanding of road signs, improving their ability to make informed decisions while driving.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation Instructions](#installation-instructions)
- [Usage Guidelines](#usage-guidelines)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Real-Time Sign Classification**: Detects and classifies traffic signs using a Convolutional Neural Network (CNN).
- **User-Friendly Interface**: Intuitive graphical user interface (GUI) that allows for easy image uploads and sign classification.
- **Multilingual Support**: Translates traffic signs into different languages using the Google Translator API.
- **Model Training Visualization**: Tracks and visualizes accuracy and loss metrics during model training.

## Technologies Used
- **Programming Language**: Python
- **Libraries/Frameworks**: 
  - Keras
  - TensorFlow
  - OpenCV
  - Matplotlib
  - Pandas
  - Tkinter
  - Google Translator API
- **Model Architecture**: Convolutional Neural Network (CNN)


Installation Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/Real-Time-Traffic-Sign-Recognition.git
Navigate to the project directory:

bash
Copy code
cd Real-Time-Traffic-Sign-Recognition
Install the required dependencies:

bash
Copy code
pip install tensorflow keras scikit-learn matplotlib pandas pillow
Train the model by running:

bash
Copy code
python traffic_sign.py
Note: The training process may take some time.

After the model is trained, launch the main application:

bash
Copy code
python fgui.py
This will open the graphical interface for sign detection and classification.

