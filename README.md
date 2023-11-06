# ASL-Alphabet-Recognition-
"Fundamentals of Data Science" final project. December 2023.

Abstract: The main idea behind our project was to make sign language accessible to more people, to promote social inclusion of signing people. In order to do so, we decided to start with a simple task, namely classifying ASL alphabet images.
At first we tried feeding a fully-connected net with pre-processed images: we resized the images, converted them in black and white and then we used different filters (gradient descent, sharpening and hysteresis) to detect the edges.
Although fully-connected networks make no assumptions about the input, they tend to perform less and aren’t good for feature extraction, hence we decided to change approach and use a Convolutional Neural Network (CNN).

In this repository you can find two files, namely:

initial_idea.pdf the first presentation done to explain our idea for the project;
code.ipynb containing the python code;
report.pdf containing the final report used for the presentation.
Group members: Alvetreti Federico, Bassani Aurora, Corrias Ioan, Luciani Erica, Pelliccioni Gabriele.
