# Facial Recognition
Recognize faces using Python with the world's simplest face recognition library.

![chatbot](Recognize faces using Python with the world's simplest face recognition library.)

### Requirements
    Python = 2.x.x
    Flask
    Aiml
    pip

## Installation

1. Clone and navigate to FaceRecognition directory.

2. Install the required packages.
    ```bash
    pip install -r requirements.txt
    ```

3. Run the CreateDataset.py file which will open the camera of the PC and collects your images(Do this for all the faces you want to recognise).
    ```bash
    python CreateDataset.py
    ```
4. Run the train.py file which train the images captured.
    ```bash
    python train.py
    ```
5. Run the recogniser.py file which will open the camera and detects live faces.
    ```bash
    python recogniser.py
    ```
