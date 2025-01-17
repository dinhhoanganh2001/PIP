# Face-Recognition
A web application using pre-train model for Face Recognition.

## Summary
The project contains 3 major modules:
* **AI Module**: Face Recognition, using **face_recognition** python library to calculate the distance between images.
* **Software Module**: A **Flask** web application which contains some features such as authentication (Login/SignUp), managing user profiles, sales application, checking record.
* **Database Module**: Using **Sqlite** for simple storage.

My team has total 5 members, I'm responsible for both 3 modules.

## Problem
The problem can be described as:
* Customer can buy our AI applications on website.
* After buying, customer can use face recognition feature.
* About face recognitioin feature, It can identify a user if he/she was added to database before.

## Installation

### Environment
#### For AI module and gateway:
```bash
pip install requirements.txt
```


#### For Flask application:
* Highly recommend **PyCharm** IDE to run the code.
* The project folder is ```application```. So you just clone this, build and run with your IDE in localhost.
### Data-set
* Since I used pre-trained model to get embedding, so I didn't have to train a network to learn the similarity and difference between faces, that's mean I only need the image database of members in the house. 


## Web Application
<p style="text-align:center;"><img src="https://firebasestorage.googleapis.com/v0/b/pipai212.appspot.com/o/Product_des.png?alt=media&token=4acc0d22-ad7a-44a0-97d8-4c02d15beab3" width="500"></p>

<p style="text-align:center;"><img src="https://firebasestorage.googleapis.com/v0/b/pipai212.appspot.com/o/play.png?alt=media&token=3b63f969-c8ee-41c5-ab37-6562693e2c3d" width="500"></p>

## Challenges
* Lacking of cloud server to maintain the python code, I have to run the Python script on local host.
* Web applicaton is not optimize.
* Lacking of database server.

## What next?
* AI: next time, I will use transfer learning and train the network based on VietNamese Faces data-set, implement the algorithm myself.
* Software: increase UI for easier look (change to use another framework for building web app).
* Database: use another database server such as Microsoft SQL Server

## References
[1] Ian Sommerville (2011), Software Engineering (ninth edition).  
[2] Fran ̧cois Chollet (2021),Deep Learning with Python, Second Edition.
