# Face-Emotion-Recognition
# Problem Statement
The Indian education landscape has been undergoing rapid changes for the past 10 years owing to
the advancement of web-based learning services, specifically, eLearning platforms.
Global E-learning is estimated to witness an 8X over the next 5 years to reach USD 2B in 2021. India
is expected to grow with a CAGR of 44% crossing the 10M users mark in 2021. Although the market
is growing on a rapid scale, there are major challenges associated with digital learning when
compared with brick and mortar classrooms. One of many challenges is how to ensure quality
learning for students. Digital platforms might overpower physical classrooms in terms of content
quality but when it comes to understanding whether students are able to grasp the content in a live
class scenario is yet an open-end challenge.
In a physical classroom during a lecturing teacher can see the faces and assess the emotion of the
class and tune their lecture accordingly, whether he is going fast or slow. He can identify students who
need special attention. Digital classrooms are conducted via video telephony software program (exZoom) where it’s not possible for medium scale class (25-50) to see all students and access the
mood. Because of this drawback, students are not focusing on content due to lack of surveillance.
While digital platforms have limitations in terms of physical surveillance but it comes with the power of
data and machines which can work for you. It provides data in the form of video, audio, and texts
which can be analysed using deep learning algorithms. Deep learning backed system not only solves
the surveillance issue, but it also removes the human bias from the system, and all information is no
longer in the teacher’s brain rather translated in numbers that can be analysed and tracked.

## Dataset
We have built a deep learning model which detects the real time emotions of students through a webcam so that teachers can understand if students are able to grasp the topic according to students' expressions or emotions and then deploy the model. The model is trained on the Face Expression Dataset.

This dataset consists of 35887 grayscale, 48x48 sized face images with seven emotions -angry, disgusted, fearful, happy, neutral, sad and surprised.

![image](https://user-images.githubusercontent.com/85746056/146337953-022092b3-7949-4b4d-a752-a080390fdd91.png)
#  Model Building Using CNN
![model](https://user-images.githubusercontent.com/85746056/146340046-299eb139-58a5-439f-a011-c62e4e8515f6.png)
Validation Accuracy achived by model is 65%.

![output](https://user-images.githubusercontent.com/85746056/146340966-1784d293-b84d-44d1-a9ef-1f89eaef5547.png)
## Dependencies
Numpy =1.21.2

Streamlit =0.87.0

Keras =2.4.3

Opencv-contrib-python-headless

Tensorflow-cpu

Streamlit_webrtc
## Accuracy and Loss Graph
![image](https://user-images.githubusercontent.com/85746056/146380609-e4c175e5-9f26-4b6b-8595-c962d6e7acd7.png)
The model which was created using CNN that gave training accuracy of 80% and validation accuracy of 65%. 



