# Smart Attendance Management using Face Recognition. 


* In this project, KNN Classification is to identify whether the person is absent or present. KNN is a supervised method used for classification. 

* Two files called add_faces.py and test.py are created. In add_faces new user will be added. First, the name of the new user is taken as an input and then 100 images of the user are captured. 

* An inbuilt file 'data/haarcascade_frontalface_default.xml' is used to
save the captured face features of the new user. This data is saved in a pickle file.

* Next, test.py file is to be executed where the actual prediction of the user's face takes place. 

* Code Description.pdf file contains detailed working of the code. 

## Output

+ Add a new User. 

/Users/samiksha/Desktop/Screenshot 2024-05-22 at 12.42.02 AM.png


+ 100 frames are captured to learn the new user's facial features.
 
/Users/samiksha/Desktop/Screenshot 2024-05-22 at 12.42.13 AM.png

+ Afterwards, the user is identified correctly by their name. 

/Users/samiksha/Desktop/Screenshot 2024-05-22 at 12.42.26 AM.png

+ Attendance is marked in the pickle file.

/Users/samiksha/Desktop/Screenshot 2024-05-22 at 12.42.37 AM.png
