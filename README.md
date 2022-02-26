# ABNORMAL EVENT MODELLING DETECTION

## An Efficient Rule Based Algorithm for Fire Detection on Real Time Images

### Problem Definition:

The proposed algorithm handles YCbCr color model to decouple the luminance and chrominance which more discriminate the color than RGB color model. This algorithm has been tested on fire and fire like images which results in 97.95 % detection accuracy.

### Thesis Guide: 
Dr.T Senthil Kumar, Asst. Professor, CSE, Amrita School of Engineering.

### Team:
P.SRIDHAR


### Proposed Algorithm:
Algorithm: Proposed Fire Segmentation
Input: RGB Color Image
Process:
1.	Convert RGB color space into YCbCr color space. 
2.	Apply the rules on the image. 
3.	Applying each rule results is a segmented binary image.
4.	Perform logical AND on the segmented binary image.
Output: Binary Image


### Screenshots of the application:






### Results:

The proposed method assessed with Khatami et al (2015a, 2015b)
Method	TPR	FPR	ACCURACY
Proposed Method	0.77	0.23	0.98
Khatami et.al (2015a)	0.45	0.54	0.92
Khatami et.al (2015b)	0.57	0.42	0.93



### Conclusion:

Reliable real time fire detection system is essential for smart buildings. The conventional and fast fire detection algorithm has low detection accuracy and true positive rate. The proposed method utilize YCbCr color space which effectively separate the luminance and chrominance, and is more reliable during illumination changes.The proposed method has few limitations; we used a dataset so this system detects nested fire color red, orange and yellow only even though it gives high detection accuracy and optimum true positive rate; it cannot detect the fire with more accuracy at early stage. Alternate image acquisition modality like thermal imaging give supplementary data for fire detection. Thus this proposed algorithm is best suited in controlled smart buildings with vision systems.







