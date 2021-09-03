# Colour-Detection-using-Pandas-OpenCV

## What is Colour Detection? 
🔴🔵🟢🟡🟠⚫⚪
Colour detection is the process of detecting the name of any color. Well, for humans this is an extremely easy task but for computers, it is not straightforward. Human eyes and brains work together to translate light into color. Light receptors that are present in our eyes transmit the signal to the brain. Our brain then recognizes the color. Since childhood, we have mapped certain lights with their color names. So here I will be using somewhat same strategy to detect color names.


https://user-images.githubusercontent.com/61706379/131951878-4b6e3f8d-9f2b-4880-b374-2327ed142933.mp4

![colour-detection](https://user-images.githubusercontent.com/61706379/131952250-144d3a2d-d823-437b-af75-394ffab8cfa9.png)

### About the Python Project
In this color detection Python project, we have build an application through which we can automatically get the name of the color by clicking on them. So for this, we had a data file that contains the color name and its values. Then calculate the distance from each color and find the shortest one.

### The Dataset
Colors are made up of 3 primary colors; red, green, and blue. In computers, we define each color value within a range of 0 to 255. So in how many ways we can define a color? The answer is 256*256*256 = 16,581,375. There are approximately 16.5 million different ways to represent a color. In our dataset, we need to map each color’s values with their corresponding names. But don’t worry, we don’t need to map all the values. We used a dataset that contains RGB values with their corresponding names. 

### Colors Dataset

The colors.csv file includes 865 color names along with their RGB and hex values.

