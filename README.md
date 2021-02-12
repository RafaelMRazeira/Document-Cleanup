# Document-Cleanup

## Description of a problem

Many image processing applications make use of digitalized textual data. However, the presence of any type of noise can create difficulties in post-processing information, such as on OCR detection. To improve the information manipulation on such data, a previous image processing step is required.

In light of this idea, a set of text paragraphs containing plain English language was collected. Different font styles, size, and background noise level were arranged to simulate the a variety of scenarios.

## Objective

The objective of this test is to evaluate the possible image processing methods that could fix the text samples. Note that the samples have a different type of background noise and present a set of text fonts. Therefore, the candidate should provide a flexible algorithm that can correctly detect what is text characters and background noise, offering a clean version of each text paragraph as result.

## Run Solution 

To run this solution please: 

1. Install the requirements.txt in python enviroment or not
2. Change the img_path_test variable to path of a image you want see the image processing utilised in this solution
3. Change the noise_images_dir variable to path to all noised data send in this test
4. Open the Document_Cleanup.ipynb file in jupyter notebook or vscode with python extension# Document-Cleanup
