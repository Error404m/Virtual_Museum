## Virtual_Museum
AGA Course Project

#### Faculty Name- Prof. Anupam Agarwaal

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#built-with">Built With</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#How-to-use">How to use</a></li>
    <li>
      <a href="#model-predictions">Model Predictions</a>
     
    </li>
     <li><a href="#team-members">Team Members</a></li>
     <li><a href="#Important-Project-Links">Important Project Links</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>


## About The Project
A virtual museum is a digital entity that draws on the characteristics of a museum, in order to complement, enhance, or augment the museum experience through personalization, interactivity and richness of content.

<!-- ## Team Members
|   Enrollment No.  |   Name   | Github ID |
|   --------------  |   ----   | -------- |
|    IIT2019239  |  Mrityunjaya Tiwari  | [Error404m ](https://github.com/Error404m) |
|    IIT2019222  |   Rauank Singh Rathore  | [Error404r ](https://github.com/Error404r) |
|    MIT2021006  |   Aditya Gupta |  [Amanjeetk11 ](https://github.com/Amanjeetk11) |
|    MIT2021045  |   KM Khushboo  | [Jyo123-verma ](https://github.com/Jyo123-verma) |


## Built With
<ul>
   <li>Unity3D</li>
   <li>Blender</li>
   <li>Google Script</li>
  <li>Javascript</li>
</ul>


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
  * Create the Virtual Environment
  ```sh
  $ python3 -m venv venv
  ```
  
  * Activate the virtual environment
  ```sh
  $ source venv/bin/activate
  ```
  
  * Install Falsk
  ```sh
  $ pip3 install Flask
  ```
  
  * Install NumPy
  ```sh
  $ python -m pip install numpy
  ```
  
  * Install Pandas
  ```sh
  $ python -m pip install pandas
  ```
  
  * Install Matplotlib
  ```sh
  $ python -m pip install matplotlib
  ```
  
  * Install OpenCV
  ```sh
  $ python -m pip install opencv-python
  ```
  
  * Install Keras
  ```sh
  $ python -m pip install keras
  ```
  
  * Install TensorFlow
  ```sh
  $ python -m pip install tensorflow
  ```
  
 ### Installation


1. Clone the repo
   ```sh
   git clone https://github.com/Amanjeetk11/ivp.git
   ```
2. Change directory to main file
   ```sh
   cd model_codes
   ```
3. Install requirements.txt
   ```sh
   pip install requirements.txt 
   ```
4. Set the FLASK_APP system variable
   ```sh
   $ export FLASK_APP=app.py
   ```
5. Run Flask
   ```sh
   $ flask run
   ```
Visit http://127.0.0.1:5000 to see your app in action 

<!-- Usage -->
## How to use
1.Go through webpage link http://127.0.0.1:5000 
<br> <img src="ss/landing_page.png"  height="370" />

2. Tap on choose file.
3. Upload or click picture of crops.
4. Click on predict

Now system will auto show status of crops ,if disease detected it will shoe name and their cure.


<!-- Usage -->
## Model Predictions

 > ### When no disease detected on plant
  
 <br> <img src="ss/healthy_plant.png"  height="370" /> <br>
  
 > ### When no disease detected on plant leafs
<br>  <img src="ss/healthy_plant_leaf.png"  height="370" /> <br>
  
 > ### When disease detected on plant
 <br> <img src="ss/dis_palnt.png"  height="370" /> <br>
  
 > ### When disease detected on plant leafs
 <br> <img src="ss/dis_plant_leaf.png"  height="370" /> <br>
 
 > ###    Disease cure recommendations
 <br> <img src="ss/dis_rec.png"  height="370" /> <br>
 
<!-- Acknowledgements -->
## Team Members  
   
| Profile | Name | Enrollment Number | 
| :-------------: | :-------------: | ------------- |
| <img src='https://dbms.redixolabs.in/img/jprmbt1.jpeg' width='55' height='55'> | Mrityunjaya Tiwari| IIT2019239 
| <img src='https://dbms.redixolabs.in/img/RAUNAK.jpeg' width='55' height='55'> | Raunak Singh Rathore| IIT2019222
| <img src='https://dbms.redixolabs.in/img/20210429_210617.jpg' width='55' height='55'>| Mr. Aditya Sir| IIB2019006  
| <img src='https://dbms.redixolabs.in/img/jyoti.jpeg' width='55' height='55'> | Khushbooooo Mam| IIT2019202

<!-- Important Project Links -->
## Important Project Links
* [Website Frontend (only for demo) ](https://amanjeetk11.github.io/ivp/Web%20part/index.html)
* [Google colab Link](https://colab.research.google.com/drive/1s0LwOQbv54WbKTxh9PvEtcFiVrercUxK?usp=sharing)
* [Report Docs](https://docs.google.com/document/d/1KTymgQa6YGZmuw8pNrisI0JCPPe5htt6/edit#)
* [PPT Presentation](https://towardsdatascim/build-your-first-machine-learning-model-using-tensorflow-d61b9b2b7d5e)



<!-- Acknowledgements -->
## Acknowledgements
* [Deploy flask app ](https://www.freecodecamp.org/news/how-to-build-a-web-application-using-flask-and-deploy-it-to-the-cloud-3551c985e492/)
* [Flask App tutorial](https://www.digitalocean.com/community/tutorials/how-to-make-a-web-application-using-flask-in-python-3)
* [Training model with Tensorflow](https://towardsdatascience.com/build-your-first-machine-learning-model-using-tensorflow-d61b9b2b7d5e)
* [deploy model using Keras](https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/)
