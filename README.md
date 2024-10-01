# Object Detection with MobileNet and Streamlit
This project demonstrates how to use the MobileNet model, a pre-trained deep learning model, for object detection and image classification through a user-friendly web interface built using Streamlit.

#### Features
- Upload an image file through the Streamlit app.
- The image is processed and classified using the MobileNet model pre-trained on the ImageNet dataset.
- The top prediction label is displayed as the identified object.

#### Technologies Used
- MobileNet: A lightweight, efficient deep learning model trained on ImageNet, suitable for mobile and embedded vision applications.
- TensorFlow/Keras: Deep learning framework used to load and apply the MobileNet model.
- OpenCV: Used for image processing tasks such as resizing.
- Streamlit: Framework to create the web interface for image upload and displaying results.

#### Installation
1. Clone the repository
```
git clone https://github.com/yourusername/mobilenet-streamlit-app.git
cd mobilenet-streamlit-app
```
3. Install required packages
```
pip install tensorflow opencv-python-headless streamlit
```
4. Run the Streamlit app
```
streamlit run app.py
```

#### Usage
- Open the app in your browser at http://localhost:8501.
- Upload an image in .jpg, .jfif, or .png format.

The app will classify the uploaded image and display the most likely object name.
Jupyter Notebook Version

If you prefer running the model and image classification locally in a notebook environment, a Jupyter notebook version of this project is included. You can execute each step and modify the code as needed.

Folder Structure
```
mobilenet-streamlit-app/
│
├── app.py              # Main Streamlit application
├── mobilenet_notebook.ipynb   # Jupyter notebook version
├── requirements.txt    # List of dependencies
├── README.md           # This file
```
