Recognizing Authors from Scans of Polish Handwritten Text Using the ResNet Architecture
Introduction

This project focuses on recognizing authors of Polish handwritten text based on scanned documents. 
It utilizes deep learning, specifically the ResNet50 architecture, to analyze images and identify individual writing styles.

Dataset
The project uses the Polish Handwritten Text (HPT) dataset, which contains scanned texts from eight different authors. 
Each text is in bitmap format and includes metadata about word boundaries.

Preprocessing Methods
Two approaches to image segmentation are used in the project:

Word Segmentation: Isolates individual words from scanned images, treating each word as a separate input for the neural network.
Tile Segmentation: Divides each image into tiles with a fixed count per scan, regardless of word boundaries.

Model Architecture
The model employs the ResNet architecture, which is known for its effectiveness in image recognition tasks. 
The project experiments with ResNet50 and ResNet101 versions.

Experiments and Results
Various experiments were conducted using both word and tile segmentation methods. 
The results show that both methods achieve high accuracy, with the tile method being significantly faster and requiring less training data.
