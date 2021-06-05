# Real-time-Vernacular-Sign-Language-Recognition-using-MediaPipe-and-Machine-Learning
<a href="https://www.ijrpr.com/uploads/V2ISSUE5/IJRPR462.pdf"><img src="https://img.shields.io/badge/IJRPR-Publisher-blue"><a/> <a href="https://google.github.io/mediapipe/solutions/hands.html"><img src="https://img.shields.io/badge/Google%20Framework-MediaPipe-brightgreen"/></a> <a href="https://arxiv.org/abs/2006.10214"><img src="https://img.shields.io/badge/MediaPipe-Hands-brightgreen"/></a> <br>
<img alt="Python" src="https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white"/> <img alt="NumPy" src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" /> <img alt="Pandas" src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" /> <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-%23F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white" />
  
  
### Abstract 
The deaf-mute community have undeniable communication problems in their daily life. Recent developments in artificial intelligence tear down this communication barrier. The main purpose of this paper is to demonstrate a methodology that simplified Sign Language Recognition using MediaPipe’s open-source framework and machine learning algorithm. The predictive model is lightweight and adaptable to smart devices. Multiple sign language datasets such as American, Indian, Italian and Turkey are used for training purpose to analyze the capability of the framework. With an average accuracy of 99%, the proposed model is efficient, precise and robust. Real-time accurate detection using Support Vector Machine (SVM) algorithm without any wearable sensors makes use of this technology more comfortable and easy.
  
### Datasets Used
 <img src="Figures/Dataset_Images_TABLE%201/american_alphabets.jpg" height="300" width="300"/> <img src="Figures/Dataset_Images_TABLE 1/american_numbers.jpg" height="300" width="300"/>
  <img src="Figures/Dataset_Images_TABLE 1/indian_alphabets.jpg" height="300" width="300"/> <img src="Figures/Dataset_Images_TABLE 1/turkey_numbers.jpg" height="300" width="300"/>
  <img src="Figures/Dataset_Images_TABLE 1/Italian.jpg" height="300" width="300"/>


### Architecture
  <img src="https://github.com/arpita739/Real-time-Vernacular-Sign-Language-Recognition-using-MediaPipe-and-Machine-Learning/blob/master/Figures/FIGURE1.png">
  
### Real-Time Prediction of American Sign Language
  
 <img src="Figures/Real_time_images_FIGURE 4/Screenshot 2021-04-05 at 10.44.55 PM_auto_x2.png" width="400"/> <img src="Figures/Real_time_images_FIGURE 4/Screenshot 2021-04-05 at 10.46.01 PM_auto_x2.png" width="400"/>
  
### Step by step process to build Sign Language Recognition project using MediaPipe
  <ul>
  <li>Run <code>!pip install mediapipe</code> to install Mediapipe in your Windows/Mac OS.</li>
  <li>Use <code>EXTRACT_DATA.py</code> to Pre-Proprocess dataset. That is extracting landmarks as features using Mediapipe.</li>
  <li>Build your own <strong> Machine Learning </strong> Model. Also, you can have a look at <a href="https://github.com/arpita739/Real-time-Vernacular-Sign-Language-Recognition-using-MediaPipe-and-Machine-Learning/tree/master/Detection"/> Detection </a> folder for checking my Machine Learning Models for different datasets.</li>
  <li>Use <code>hand_detection_webcam.py</code> to test your model in real-time environment using Mediapipe Technology</li>
  </ul>
  
### Research Article
<object data="https://www.ijrpr.com/uploads/V2ISSUE5/IJRPR462.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://www.ijrpr.com/uploads/V2ISSUE5/IJRPR462.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://www.ijrpr.com/uploads/V2ISSUE5/IJRPR462.pdf">Download PDF</a>.</p>
    </embed>
</object>


  
  
  
  
  
 
  
