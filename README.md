# Vehicle-Number-plate-detection


## Automatic number plate recognition (ANPR):
Number Plate recognition, also called License Plate realization or recognition using image processing methods is a potential research area in smart cities and the Internet of Things. An exponential increase in the number of vehicles necessitates the use of automated systems to maintain vehicle information for various purposes.

![ANPR](ANPR.jpg)

## Implementation: 
In the proposed algorithm an efficient method for recognition of Indian vehicle number plates has been devised. We are able to deal with noisy, low illuminated, cross angled, non-standard font number plates. This work employs several image processing techniques such as, morphological transformation, Gaussian smoothing, Gaussian thresholding and Sobel edge detection method in the pre-processing stage, afterwhich number plate segmentation, contours are applied by border following and contours are filtered based on character dimensions and spatial localization. Finally we apply Optical Character Recognition (OCR) to recognize the extracted characters. The detected texts are stored in the database, further which they are sorted and made available for searching. 

This project will work efficiently in recognizing owner's vehicle in small Institutions/Housing societies/Apartments. We can further modify the code to use it in other areas where ANPR is necessary. 

![Output](Result.png)


