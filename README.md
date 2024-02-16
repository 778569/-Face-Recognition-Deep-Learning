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


## Part 03 - Representing a face as a set of Measurements
 measure each eye, size of the cheekbones  and the width of mouth and so on <br><br>
 ![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/37610377-e426-485e-a5e5-b531282e7f7c) <br><br>

Here are two face , lets take three measurements for each face
i.	Length of nose – 2.5 (left) | 2 (right)
ii.	Width of mouth – 2.5 and  3 
iii.	Distance of one eye to other 4 and 3.5<br><br>
![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/633e95f2-1f57-4f65-932a-3af15732929f) <br><br>

That distance is relay small or close each other(two point) that may be a same person.<br><br>

![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/6c3080fb-404d-4700-b4ec-e742dc1d0a86)<br><br>

using face_encodings library - output 128 values <br><br>
![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/5d586430-75b6-4cfc-8878-b45cd34ff5e4) <br><br>


## Part 05 Euclidean distance 


Face distance threshold – 
Set a face maximum distance that is still considered the same face . 
Lets assume the threshold value is 0.6.
*  If the distance (a,b) > 0.6, not , match
* 	If the distance (a,b) =< 0.6, they  match
*  he lower the distance , the better the match
<br><br>
![image](https://github.com/778569/Face-Recognition-Deep-Learning/assets/52319671/17a745ee-acdd-47de-b872-3af7e3737052)

## Part 6 - Fun Uses of face recognition

* How to drawaing a image (makeup)
* Choose best image from collection of images 

