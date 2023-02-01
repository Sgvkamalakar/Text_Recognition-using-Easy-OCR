# Text/Number detection and recognition from Engineering drawings

## Problem Statement:
When analyzing engineering complex engineering drawings, some of the numbers are covered by text.
  a. How to identify such numbers/ text?
  b. How to interpret such numbers/text?


## Workflow:
1. Image preprocessing
2. Segmentation
3. Featyre Extraction
4. Text/Number Recognition
5. Post processing


## Work flow Contd..
1. **Image Preprocessing**: This involves cleaning up the image to remove any noise or distortions and enhance the quality of the image for better text recognition.

There are several image pre-processing methods that are commonly used in text recognition from engineering drawings, including:
* Noise reduction: Removing noise from the image to improve the quality of the text. This can be done using techniques such as median filtering, Gaussian filtering, or morphological operations.
* Binarization: Converting the image to a binary format to separate the text from the background. This is usually done using thresholding techniques, such as global thresholding, adaptive thresholding, or Otsu's method.
* Image normalization: Adjusting the brightness and contrast of the image to improve the visibility of the text. This can be done using techniques such as histogram equalization or contrast stretching.
* Image resizing: Resizing the image to a suitable resolution to improve the accuracy of the text recognition.
* Skew correction: Correcting the skew of the image to make the text appear horizontal. This can be done using techniques such as Hough transform or projection profile analysis.
* Image cropping: Removing the unnecessary parts of the image to focus on the text region.


2. **Image segmentation**: The image is divided into smaller regions to isolate the text areas.
Image segmentation is the process of dividing an image into smaller regions to isolate the text regions. There are several image segmentation methods commonly used in text recognition from engineering drawings, including:

* Thresholding: Separating the text from the background using thresholding techniques, such as global thresholding, adaptive thresholding, or Otsu's method.
* Connected Component Analysis (CCA): Labeling connected pixels that form a single text region.
* Region-based segmentation: Segmenting the image based on properties of the regions, such as size, shape, or intensity.
* Edge-based segmentation: Detecting edges in the image and using them to segment the text regions. This can be done using techniques such as Canny edge detection or Sobel edge detection.
* Object Proposal: Generating a set of candidate regions that may contain text, and then refining the proposals to extract the text regions.
* Deep Learning-based segmentation: Using deep learning techniques, such as Convolutional Neural Networks (CNNs) or Fully Convolutional Networks (FCNs), to segment the text regions from the image.


3. **Feature Extraction**: The text regions are analyzed to extract features such as character shapes, strokes, and spacings
Feature extraction is the process of analyzing the text regions to extract relevant features that can be used for character recognition. Some of the commonly used feature extraction methods in text recognition from engineering drawings are:

* Shape-based features: Extracting features based on the shape of the characters, such as the number of strokes, the aspect ratio, or the number of corners.
* Texture-based features: Extracting features based on the texture of the characters, such as the intensity, gradient, or frequency.
* Context-based features: Extracting features based on the context of the characters, such as the relationships between adjacent characters, or the spacing between characters.
* Structural features: Extracting features based on the structure of the text, such as the arrangement of characters into lines and words.
* Deep learning-based features: Extracting features using deep learning techniques, such as Convolutional Neural Networks (CNNs) or Recurrent Neural Networks (RNNs).


4. **Number/Text recognition**: 
Number and text recognition are the processes of recognizing individual characters and combining them to form words and sentences, respectively. Some of the commonly used character/text recognition methods in text recognition from engineering drawings are:

* Template matching: Comparing the extracted features with a pre-defined set of templates to recognize the characters.
* Optical Character Recognition (OCR): Using machine learning algorithms, such as Support Vector Machines (SVMs) or Artificial Neural Networks (ANNs), to recognize characters based on the extracted features.
* Handwritten text recognition: Recognizing handwritten text using techniques such as HMM, DTW, or deep learning.
* Dictionary-based recognition: Recognizing characters based on the frequency of occurrence in a pre-defined dictionary.
* Segmentation-free recognition: Directly recognizing text without the need for segmenting the characters first, using techniques such as sliding window, connectionist temporal classification (CTC), or attention-based methods.


5. **Post-processing**: Finally, the recognized text is post-processed to correct any errors or inconsistencies and to improve the overall quality of the recognized text.
Post-processing methods are techniques used after the text recognition to improve the accuracy and readability of the recognized text. Some of the commonly used post-processing methods in text recognition from engineering drawings are:

* Error correction: Correcting errors in the recognized text using techniques such as spell checking, grammar checking, or dictionary-based correction.
* Text normalization: Converting the recognized text into a standard format, such as converting uppercase characters to lowercase, or removing special characters.
* Text cleaning: Removing unwanted characters, such as punctuation or whitespace, from the recognized text.
* Text correction: Correcting the recognized text using techniques such as fuzzy logic, voting, or consensus algorithms.
* Text refinement: Improving the layout and formatting of the recognized text to make it more readable, such as adjusting the line breaks, or adding spacing between characters.

