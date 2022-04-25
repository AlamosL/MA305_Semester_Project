# MA305_Semester_Project
Image recognition is a widely used observation technique for software to identify objects or people within an image. 
Using coding methods for sifting through databases, we will be creating a Python code to recognize objects within a camera’s frame 
of reference and accurately identify the object to the user. Our goal is to obtain multiple databases of common objects from online 
sources to use as our library of reference objects. The code will identify the individual pixels of the image and then match the pixels 
to the object library. All of the objects within the frame will be able to be identified and displayed in the output. The results of 
this project will yield a Python algorithm for precise object detection in an image. 

In these files we have attempted to pull in a large file containing images which deemed successful. We have also established how to open
and close the camera for viewing purposes.

Midterm Update: We began the machine learning coding process by incorporating Tensorflow into our code. Due to the complex nature of the 
                object reconition algorithim, the use of the Tensorflow custom python enviroment was essential in creating a model for the 
                software to decipher images. OpenCV was incorpoated to access the computer webcam which provides a live image feed to be compared
                to the machine learned data. This is what the computer will use to sift through determinate and indeterminate images.
                
Final Update: Static image object detection was sucessful using TensorFlow in Python. Models were created but not utilized due to hardware constraints
              for providing a live feed. Accuracy level potentially needs improvement in order to output correct object detection to the user. 
              Overall, the code deemed sucessful for static image object detection and produced correct outputs with varying accuracy. 

https://github.com/AlamosL/MA305_Semester_Project.git
