# PartMaster

PartMaster is a computer vision project  designed to  identify and categorize various car components using deep learning techniques and convolutional neural networks . This project is aimed at providing a solution for automating car part recognition tasks, with potential applications in the automotive industry, inventory management, maintenance, and more.

## Overview

Car Part Recognition employs deep learning techniques, specifically the Inception-ResNet architecture, to achieve accurate part recognition. Key components of this project include:

### 1. Deep Learning Model

The core of the project is a deep learning model trained to recognize different car parts. The model has been trained on a diverse dataset of car part images to ensure accurate identification.

### 2. Flask Web Application

The project includes a  Flask-based web application. Users can upload images of car parts via the web interface, and the model provides real-time predictions, identifying the specific part in the image.

![Car Part Recognition GIF](https://github.com/OliverNagy10/PartMaster/blob/main/tutorial.gif)



## Prerequisites

Before using the app, make sure you have the following installed:

- Python (version 3.6 or higher)
- pip (Python package manager)

## Getting Started

Follow these steps to set up:

1. **Download Project Files**:

   Download the project files from the following Google Drive folder: [Google Drive Project Folder](https://drive.google.com/drive/folders/1SfCNkofSfip6KsEe3v9VULVN22nAFodM?usp=sharing)

   Extract the downloaded ZIP archive to a location of your choice on your local machine.

2. **Install Dependencies**:

   Navigate to the project directory where you extracted the files.

   Install the required dependencies:

   ```bash
   pip install -r requirements.txt
 
 3. **Run the App**
    
    Start the Flask application by running the following command from the project directory:
    
    ```bash
     python app.py


 4. **Access the app**

    Open a web browser and go to the address provided in the previous step (e.g., http://127.0.0.1:8080/). You should see the home page of the app.

 4. **Upload Image**

    Click on the "Choose File" button to upload an image of a car part that you want to recognize.

6. **View Prediction**

   After uploading an image, the app will process it and display the predicted car part label on the screen.
