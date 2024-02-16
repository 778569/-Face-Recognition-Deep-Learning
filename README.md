# Face-Recognition-Deep-Learning
Face recognition is used for to unlocking cell phones. And with recent advancements in deep learning,In this repository how to develop a face recognition system that can detect faces in images, identify the faces, and even modify faces with "digital makeup" like you've experienced in popular mobile apps

# Part 01 - Face Recognition Pipeline Steps


Step 1: Locate and extract faces from each image
Step 2: Identify facial features in each image
Step 3: Align faces to match pose template
Step 4: Encode faces using a trained neural network
Step 5: Check Euclidean distance between face encodings

![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/ec1af474-671d-443d-b8af-bd9e84abcd1e)<br><br>

Use of face recognition 
1.	Identify verification’
2.	Automatically organizing new photo libraries by person.
3.	Tracking a specific person
4.	Counting unique people
5.	Finding people with similar appearances. 

# Install libaries

```
pip install pillow 
pip install face-recognition
```

if you are using google Co-lab set to Run time to GUP

# Part 02 - Face Recognition

Sliding window classifier<br><br>
![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/75838b3b-cedf-4010-8028-a9ecec082304)<br><br>

Histogram of Oriented Gradients (HOG)<br><br>
![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/b465d983-53df-4904-a6b0-760d9b254522)<br><br>

Analyzing an Image as a Histogram of Oriented Gradients <br><br>

![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/b0927838-0036-4a9e-abdb-d123de47e839)<br><br>

![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/7e306434-1e8a-429f-bdf6-044116c6fde6)

# face land mark estimation
Identify key pint on the face – tip of the nose , center of the eye

![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/30fdacf3-a01e-48e3-bd63-8c41a29f6c20)<br><br>

Identifying Face Landmarks with a Machine learning model

![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/6f09b7f9-4bb4-4060-8c4e-3681fbf187bb) <br><br>

Calculate affine Transform <br><br>

![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/30f20205-5e4e-4584-8eba-7e7e2d794917) <br><br>

Finally - <br><br>

![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/b59d4f7f-3421-42ba-8a92-de49584ed693) <br><br>



