# ABNORMAL EVENT MODELLING DETECTION

## An Efficient Rule Based Algorithm for Fire Detection on Real Time Images

### Problem Definition:

The proposed algorithm handles YCbCr color model to decouple the luminance and chrominance which more discriminate the color than RGB color model. This algorithm has been tested on fire and fire like images which results in 97.95 % detection accuracy.

### Thesis Guide: 
Dr.T Senthil Kumar, Asst. Professor, CSE, Amrita School of Engineering.

### Team:
P.SRIDHAR


### System Design:
Algorithm: Proposed Fire Segmentation
Input: RGB Color Image
Process:
1.	Convert RGB color space into YCbCr color space. 
2.	Apply the rules on the image. 
3.	Applying each rule results is a segmented binary image.
4.	Perform logical AND on the segmented binary image.
Output: Binary Image







