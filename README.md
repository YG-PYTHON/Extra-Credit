# Extra-Credit
Color detection using panda and opencv

The process of detecting the name of any color in an image is known as color detection. This is an exceedingly simple task for humans, but it is not that simple for computers. The eyes and brains of humans work together to convert light into color. The signal is transmitted to the brain via light receptors in our eyes. The color is then recognized by our brain.

How do we identify colors in computers ?

In this project, we will build an application through which you get the name of the color by double clicking on your sample image

Libraries required

Pandas

numpy

opencv

argparse

step 1

In order to take image from user we have to create an argument parser that take the image path so we can direcly give the image path in the command prompt
And also we read the csv file with rgb values and load it into pandas dataframe

step 2

Create the draw function which calculate the rgb values of the pixeles in the image when double clicked
Then, the distance is calculated by a formula to get the corresponding color name

step 3

When double clicked the color name is shown in a rectangle box on the left upper corner of the window, we use cv2.imshow(), cv2.rectangle(), cv2.puttext() functions to achieve the result

Files included

color.py : the python script

colors.csv: a data set that conatins RGB values with their corresponding names 

sam.png : the sample image 

The datasource is the color dataset and if we were to use a different image we would only need to change the image name and format. if the image is not in the same location as the others we need to specify the full path of the image when running the code 

citation

https://www.askpython.com/python/examples/color-detection
