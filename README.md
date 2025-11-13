# Edge-Linking-using-Hough-Transformm
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image 
<img width="778" height="554" alt="image" src="https://github.com/user-attachments/assets/d8232d7e-cff9-43cb-a571-126b883a1367" />


### Greyscale Image
<img width="777" height="557" alt="image" src="https://github.com/user-attachments/assets/aa2a8c72-e510-4328-b463-e54a0defb97a" />



### Canny Edge detector output
<img width="795" height="549" alt="image" src="https://github.com/user-attachments/assets/a721af2c-8fab-4bda-a844-2e72ba6bcd46" />


### Display the result of Hough transform
<img width="791" height="558" alt="image" src="https://github.com/user-attachments/assets/3652ca55-9562-4280-a59f-9ee9adc65a1f" />


## Result:
Thus the program is written with Python and OpenCV to detect lines using Hough transform.
