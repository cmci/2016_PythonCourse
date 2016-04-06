# Kota's Notes

20160406  
Kota Miura (<miura@embl.de>)  
URL: <http://cmci.embl.de>

## Image Data Analysis

- Difference of "Image Analysis" in signal processing and in biology. 
   - "Image analysis" convensionally aims at mimicking human recognition, whereas "Bioimage analysis" aims at objective measurement, trying to avoid human recognition bias.  
- Workflows and components (algorithms)
  - Assemble components as workflow, to get numbers out of image data 
- typical workflows in biology
  - type 1: single channel image data
     - input image -> segmentation -> measurement -> numbers 
  - type 2: multi-channel image data
     - segmentation in one channel, measurement of another channel using the segmented channel 1 image. 
- General problem of segmentation
  - beef problem 
  - Signifié et signifiant (Saussure, General lingustics)  
     - Becareful not to agree with terms, but to agree with numerical definition of segmentation method.  
- Textbook: "Bioimage Data Analysis"
  - <http://bit.ly/BIAS-book>	

## Segmentation and Filtering

- Segmentation typically has 3 steps: **pre-processing, binarize, post-processing**
- pre-processing
  - principle of convolution in 1D, 2D (...nD)
  - smoothening, sharpening
  - denoising (median filter)
  - unsharp mask 
- Binarize
  - Intensity Thresholding 	
- post-segmentation filtering
  - Tuning segmented structures
  - Mathematical Morphology
    - erosion / dilation
    - opening / closing
    - distance map
    - watershed
    
## Misc.

- Bioimage Data Analysis Course
  - <http://www.embl.de/bias2016> 


