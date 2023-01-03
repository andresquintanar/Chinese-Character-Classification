# Chinese-Character-Classification
This project uses Keras Neural Networks to classify handwritten Chinese letters:

Project Description
One hundred Chinese nationals took part in data collection. Each participant wrote with a standard black ink pen all 15 numbers in a table with 15 designated regions drawn on a white A4 paper. This process was repeated 10 times with each participant. Each sheet was scanned with a resolution of 300x300 pixels.
It resulted in a dataset of 15000 images, each representing one character from a set of 15 characters (grouped in samples, grouped in suites, with 10 samples/volunteer and 100 volunteers).
Further Data Processing
The project was originally downloaded from the original project page the raw images.
This dataset is the CSV version of the original dataset uploaded to Kaggle by Gabriel Preda. The original Chinese MNIST dataset uploaded by him can be found at the following LINK. The only difference is that this dataset contains all the images and labels in the same unique file.
The dataset contains a CSV file: chineseMNIST.csv
This file contains the 15000 observations and 4098 columns. Columns 1 to 4096 represent each pixel of the image (64x64). The last two columns denote the value label and the original Chinese character
