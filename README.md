
## 🔗 Connect with me in linkedin

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/im-adarshmetimath)


## 🚀 About Me
 # Hi, I'm Adarsh ! 👋

Experienced data scientist with expertise in NLP, ML, and DL. Proficient in Python and data visualization, with a track record of developing and deploying ML models. Skilled at working with large datasets and driving data-driven decision making through cross-functional collaboration. Strong communication and leadership skills for effective mentoring and presenting to non-technical audiences.



# 3D Face Recognition with Liveness Recognition (one shot learning)

The face recognition model created using the face_recognition library and OpenCV utilizes a unique architecture called the Siamese architecture with one-shot learning.

Siamese architecture is a neural network architecture that uses two identical subnetworks that share weights and are trained simultaneously. In the case of face recognition, each subnetwork takes in an image of a face, and the outputs are compared to determine whether the faces belong to the same person or not. One-shot learning is a technique where the model is trained on just one or a few examples of each person's face.

The model is trained on a dataset of faces using the Siamese architecture and one-shot learning technique. Once the model is trained, it can recognize faces it has never seen before with high accuracy, even if it only has one or a few examples of that person's face.

The face recognition model can be used for various applications, such as security systems, attendance management systems, or identifying individuals in a group photo. The model is highly accurate and efficient, making it a valuable tool for various industries and use cases.




### Pic about architecture

![SIAMESE](https://github.com/imadarsh9686/3D-face-recognition-one-shot-learning-/blob/main/face%20reco2/seamese%20architexture.jpg)

### Pic about architecture 2

![SIAMESE](https://github.com/imadarsh9686/3D-face-recognition-one-shot-learning-/blob/main/face%20reco2/1_23mikUF3HBJGUqrX7tMKQQ.png)

## 1) Create new project virtual environment in pycharm with pyathon 3.9

- open pycharm and create virtual environment with python 3.9 


### virtual env setup

![venv](https://github.com/imadarsh9686/3D-face-recognition-one-shot-learning-/blob/main/face%20reco2/scrren%20shots/virtual%20env%20pic%20with%20python%203.9.png)




##  2) Download zip file or clone the project from git hub 

- Extrcat  files inside the new vertual environment project created
  
- Open pycharm and open the project where you extracted a files 
 

### Zip file github

![github](https://github.com/imadarsh9686/3D-face-recognition-one-shot-learning-/blob/main/face%20reco2/scrren%20shots/download%20zip%20file%20from%20github%20.png)



### Pycharm view 

![Pycharm](https://github.com/imadarsh9686/3D-face-recognition-one-shot-learning-/blob/main/face%20reco2/scrren%20shots/1%20pic%20pycharm.png)

## 3) Copy the path of the dlib library from folder (Dlib-python whl packages)
- Copy the path of dlib library 3rd one from file with name (Dlib-python whl packages)  
- see below image to copy path
### Copying path of Dlib library    

![Pycharm](https://github.com/imadarsh9686/3D-face-recognition-one-shot-learning-/blob/main/face%20reco2/scrren%20shots/2%20file%20directory%20pic%20.png)

### Copying path of Dlib library    

![Pycharm](https://github.com/imadarsh9686/3D-face-recognition-one-shot-learning-/blob/main/face%20reco2/scrren%20shots/3%20path%20of%20the%20d%20lib.png)

## 4) Installing dlib library using copied path in terminal
- open terminal below 
-  write pip install code and paste copied path after the code as show below
#### code

To install dlib 

```bash
  pip install "paste copied path here"
```


### installing dlib

![dlib](https://github.com/imadarsh9686/3D-face-recognition-one-shot-learning-/blob/main/face%20reco2/scrren%20shots/4%20install%20library%20using%20path%20in%20terminal.png)





## 5) Install other Dependency library
- Install the dependency library necessary for the project
- use below code to install 

#### code

To install dependency lib from requiremet.txt

```bash
  pip install -r requirments.txt
```

### installing dependency library from requirement.txt file

![lib](https://github.com/imadarsh9686/3D-face-recognition-one-shot-learning-/blob/main/face%20reco2/scrren%20shots/install%20libraries%20from%20requirements.txt.png)

## 6) RUN THE CODE 
- after installing evrything just run the 
newfacereco.py file
## 7) Press q to exit the web cam
