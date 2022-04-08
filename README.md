# Color Conversion
## AIM
To perform the color conversion between RGB, BGR, HSV, and YCbCr color models.

## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
<br>

### Step2:
<br>

### Step3:
<br>

### Step4:
<br>

### Step5:
<br>

## Program:

### Developed By: JAYASHREE RAO V
### Register Number: 212220230023

# i) Convert BGR and RGB to HSV and GRAY
```python

import cv2
house_color_image = cv2.imread('house.jpg')
cv2.imshow('original image',house_color_image)
hsv_image = cv2.cvtColor(house_color_image,cv2.COLOR_BGR2HSV)
cv2.imshow('BGR2HSV',hsv_image)
hsv_image1 = cv2.cvtColor(house_color_image,cv2.COLOR_RGB2HSV)
cv2.imshow('RGB2HSV',hsv_image1)
gray_image = cv2.cvtColor(house_color_image,cv2.COLOR_BGR2GRAY)
cv2.imshow('BGR2GRAY',gray_image)
gray_image1 = cv2.cvtColor(house_color_image,cv2.COLOR_RGB2GRAY)
cv2.imshow('RGB2GRAY',gray_image1)
cv2.waitKey(0)
cv2.destroyAllWindows()

```
# ii)Convert HSV to RGB and BGR





# iii)Convert RGB and BGR to YCrCb




# iv)Split and Merge RGB Image




# v) Split and merge HSV Image



## Output:

i) BGR and RGB to HSV and GRAY

![image](https://user-images.githubusercontent.com/74660507/162402864-2f00742d-f147-407c-b01f-91147b6cde93.png)

ii) HSV to RGB and BGR


iii) RGB and BGR to YCrCb


iv) Split and merge RGB Image


v) Split and merge HSV Image




## Result:
Thus the color conversion was performed between RGB, HSV and YCbCr color models.
