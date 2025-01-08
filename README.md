
# Facial Analysis App

The Streamlit Facial Analysis App is a simple web application that allows users to upload images and perform facial analysis on them. It utilizes popular libraries like OpenCV, DeepFace Numpy , Pillow , and Streamlit to create an easy-to-use interface for analyzing/predict the Age , Gender and Emotion of image.


## Features
- Upload Your Image: Users can upload their images in common formats like JPG, PNG, and JPEG with limit 200MB file size.

- Multi-Task Analysis: The app offers multiple analysis tasks, including age estimation, gender prediction, and emotion recognition. Users can select which tasks they want to perform.

- Real-Time Analysis: The app provides real-time analysis results, making it easy to understand the attributes of the faces in the uploaded image.
## Usage
- Visit the Streamlit Facial Analysis App.
- Upload your image by clicking the "Upload Your Image" button.
- Select the analysis tasks you want to perform by checking the corresponding checkboxes (Age, Gender, Emotion).
- Click the "Analyze" button to start the analysis.
- The app will display the uploaded image and the results of the selected analysis tasks.


## Project Improvement

- 1st Phase (3 Jun 2023):
In this phase of my project I make a project on jupyter notebook where I maually write a code on cell and provide a file path, there in no UI for my this project.


- 2nd Phase (22 Aug 2023):
I improve my project and this time i use a tkinter for UI. But still my project is not publically available it means till 22 August 2023 deployment is not done.


- 3rd Phase (22 Sep 2023):
I improve my project and deploy it on streamlit, still in this phase of my project i face a problem , the problem is .py file is locally run/work perfectly but after deployment it gives me an error 
(ImportError libGL.so.1 cannot open shared object file No such file or directory)
and then after some search and teacher help i resolve this problem and then i deploy my project Facial Analysis App on streamlit app.
[Link](https://facial-analysis-app-knn2jhzhrnzuga2km9xzbp.streamlit.app/)
## Installation

1. Clone the repository:

```bash
  git clone https://github.com/Hussainaquib/Facial-Analysis-App.git
  cd Facila-Analysis-App
```
2. Install the dependencies:
```bash
pip install -r requirements.txt
```
3. Run the app:
```bash
streamlit run face.py
```



    
## Dependencies
- [Streamlit](https://streamlit.io/)
- [OpenCV](https://opencv.org/)
- [Pillow](https://python-pillow.org/)
- [DeepFace](https://github.com/serengil/deepface)
## Demo

Use this web app:
[Link](https://facial-analysis-app-knn2jhzhrnzuga2km9xzbp.streamlit.app/)


## Feedback
If you have any feedback, please reach out to me at shubhamraj9051@gmail.com
