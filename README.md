# Computer-Vision-and-Image-Analysis

This project is the replication of State-of-art paper "Bringing Vision to the Blind". Our work was done as a Course understanding and capstone project for "computer-vision and image-analysis" to achieve the level of recreation from the papers given by our professor. 

This readme file contains the implementation of a fine-grained currency recognizer, a vital component of a personalized on-device visual assistant designed to enhance the independence and quality of life for the visually impaired. The system is focused on recognizing the 1 US Dollar bill and utilizes innovative techniques for real-time performance in everyday usability.

Project Overview

1. The Fine-Grained Currency Recognizer follows a sequential process to accurately identify currency and provide meaningful output. Here is an overview of the main steps involved:

2. Coarse Classifier: The input dataset is sent through the coarse classifier, which differentiates between various types of visual elements, including barcodes, text, and currency images.

3. Fine-Grained Currency Recognition: Among the detected visual elements, the currency images are selected and processed further for fine-grained recognition.

4. Preprocessing: The selected currency images undergo preprocessing to enhance their suitability for feature extraction and comparison.

5. Comparison with Template Image: The preprocessed currency image is compared with a template image to determine its similarity.

6. Clustering and Ranking: The matched currencies are clustered and ranked based on their similarity to the template image.

7. Final Output: The system provides the percent match between the template image and the input currency image, offering a reliable recognition result.
