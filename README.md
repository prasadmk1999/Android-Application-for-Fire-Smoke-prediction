
## Introduction
This project was completed by Prasad Kamble. This article details how to create a real time android mobile app image classifier and is deep-learning-language agnostic.

## Summary
The project covers
<ul>
     <li>Training deep learning model for fire-smoke predication </li> 
     <li>Real time android application for fire-smoke prediction</li>
</ul>
 Project git repository
 <ul>
  <li>https://github.com/prasadmk1999/Android-Application-for-Fire-Smoke-prediction/</li>
  </ul>


## Concepts

Deep-learning concepts
<ul>
  <li>Training.ipynb: https://github.com/prasadmk1999/Android-Application-for-Fire-Smoke-prediction/blob/main/Training.ipynb</li>
  <li>Inference.ipynb: https://github.com/prasadmk1999/Android-Application-for-Fire-Smoke-prediction/blob/main/Inference%20.ipynb</li>    
   </ul>          
Fire smoke dataset
<ul>
  <li> dataset in Master branch or https://github.com/prasadmk1999/Android-Application-for-Fire-Smoke-prediction/pull/new/master</li>
</ul>
 Fire-Smoke Android Application source code 
<ul>
    <li>https://github.com/prasadmk1999/Android-Application-for-Fire-Smoke-prediction/blob/main/src.zip</li>
</ul>
Providing security Application source code
<ul>
     <li>https://github.com/prasadmk1999/Android-Application-for-Fire-Smoke-prediction/blob/main/Security_src.zip</li>
     </ul>


## Android Application for Fire-Smoke prediction 
Detecting Fire, Smoke using Computer Vision, Open CV and PyTorch using deep learning concept 
Early fire/smoke detection plays a very important role in protecting many lives also property loss can be reduced and downtime for the operation minimized through early detection. Therefore in this project I have developed an Computer Vision & Deep Learning pipeline for fire and smoke detection.

android application which predict the fire and smoke.

## Problem Statement 
To build an android application that can detect fire and smoke in an image.The image can be either taken from gallery or capture a new image using camera.Colored bounding box has
to be drawn on the image once the fire or smoke is detected as shown in below image 


<img src="fire.png" class="center">


## Development process

development process is 4 types 
  <p><br>1)Data Collection</p>
<ul>
     <li> Data – Image type </li> 
      <li> Fire </li>
      <li> Smoke</li>
      <li> Neutral</li>
  </ul>

<p>2)Model Training using Teachable ML by Google</p> 
<p>3)Export Model to local system</p>
<p>4)Integrate to Android Application & testing</p>

<img src="development.png" width="900" height="500">

## Dataset Features
 1)Trainning dataset has 3 classes
<ul>
      <li> Fire has 1000 images  </li>
      <li> Smoke  has 1000 images</li>
      <li> Neutral  has 1000 images</li>
  </ul>
  
  
 2)Testing dataset has 3 classes
 <ul>
      <li> Fire has 100 images  </li>
      <li> Smoke  has 100 images</li>
      <li> Neutral  has 100 images</li>
  </ul>
  </p>
  
 
## Requirements
<ul>
      <li> Python3  </li>
      <li> Pytorch</li>
      <li> OpenCv</li>
      <li> Matplotlib  </li>
      <li> Numpy</li>
      <li> Tensor Flow Lite</li>
  <li> Android Studio </li>
  </ul>

## Implementation
Fire-Smoke detection.Detecting Fire, Smoke using Computer Vision, Open CV and PyTorch .Early fire/smoke detection plays a very important role in protecting many lives also property loss can be reduced and downtime for the operation minimized through early detection. Therefore in this project I have developed an Computer Vision & Deep Learning pipeline for fire and smoke detection.

## Model Structure 
 <p>
  teachable ML by Google is trained the model got the model files and it dump in android studio</p>
 <p>For training the model I have used transfer learning technique. Architecture used here is ResNet50 which is pretrained on ImageNet dataset. I have achieved validation accuracy   more than 95% using ResNet. training and graphs – ( Training.ipynb and Interference.ipynb)</p>
  <p>number  of Epoches=10 </p>

<img src="tarinEpoch10.png">
<img src="AccuEpoch10.png">

<p> Result of training where epoch = 10</p>
<img src="res10.png">

 <p>number  of Epoches=100 </p>
 <img src="epo100.png">
 <p> Result of training where epoch = 100</p>
 <img src="Res_100.png">
 
## Image output 
you can give any images to model.
<img src="imgPredict.png">

## video output
it also predict video based on input,if user give a video it will predict probability of input video is Fire,Smoke or Neutral.
<video width="100" height="100" controls>
<source src="vid.mp4" type ="video/mp4">
</video>


![vi](https://user-images.githubusercontent.com/56388677/102717106-2d12be80-4306-11eb-95a6-81e543bd9a90.gif)


 
## Android Application 

![neutral](https://user-images.githubusercontent.com/76401812/102758170-5aa84800-4398-11eb-8f52-a6747641c199.gif)
<p>it is real time fire-smoke detection application instead of making boxes it seems not good so that i made scolldown activity.its clearly visible to user.In real-time application its help to everyone.</p>


## Results
<p>Click the below link for Fire-smoke prediction app video....</p>
<p>https://user-images.githubusercontent.com/76401812/102762490-5c750a00-439e-11eb-9448-e285de5f754d.mp4</p>

<p>https://user-images.githubusercontent.com/76401812/102758170-5aa84800-4398-11eb-8f52-a6747641c199.gif</p>


## Providing security to app
<ul>
      <li> Register</li>
      <li> Login</li>
      <li> Default Login</li>
      <li> 2 Factor Authentication</li>
      <li> Logout</li>
  </ul>
  
  <p> Click the below links for above factors in application</p>
  <p>https://user-images.githubusercontent.com/76401812/102770421-23db2d80-43aa-11eb-8c96-17da303a60ee.mp4</p>
  
  Every user credentails saved in Firebase.
  
  
  
## Missing

  <p> Only uploded code part other file not added due to android source code size after zipping more than 400 MB its unable to add using git lfs and mannually its immpossible because of the remote end hung up unexpectedly so that if you people want i will show you using screenshare in googlemeet</P>
  <ul>
  <li> Email : prasadkamble0062@gmail.com </li>
  </ul>
  
## Any query 
<ul>
     <li>Name: Prasad M Kamble</li>
  <li> Email : prasadkamble0062@gmail.com</li>
  </ul>
