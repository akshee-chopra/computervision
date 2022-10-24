# computervision

This program is meant to display a regression line through different shapes of images. The point of this program is that I used the CV library to get the images into a black-and-white format so that I could properly find the regression line through them. Using NumPy's argwhere method, which takes an image as a parameter (in this case an image read from CV's imread(path) method, I could generate a list of points that represent the image and then properly calculate the regression line through it. 

In order to run this code on your computer, download the images into your laptop and use the same relative path names (ex: "shapes/star.png"). I ran this code in Jupyter Notebook. Make a new file called ComputerVision.ipynb which will hold the code. You can segment out the different code blocks inside of Jupyter Notebook as well to run each block/method indivually. You should be able to run everything as long as your shapes folder is in the same folder that you are running ComputerVision.ipynb. 
