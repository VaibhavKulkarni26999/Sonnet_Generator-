To Generate-Sonnet:
Using a character-level language model to generate sonnets in the style of William Shakespeare. This project was heavily inspired by chapter 8 of Francois Chollet's book Deep Learning with Python. I wanted to create a model similar to the one described in the book but trained on Shakespeare's sonnets instead and with files to make generating new sonnets easy for users.
File Descriptions
•	Sonnet_genetate. ipynb: Colab notebook including data loading and visualization, model training, and explaining the approach used and and results.
•	model.h5: Keras model trained on dataset1. This model is originally created, trained, and saved in the Model.ipynb notebook.

Requirements
•	Python (3.x)
•	NumPy (1.12.1 and up)
•	Keras (2.1.4 and up)
•	TensorFlow (1.5.0 and up)

Usage
The file Generate_sonnet.py loads the Keras model trained in Model.ipynb and automatically chooses a random seed text and generates 600 characters (average sonnet length) that will print out to your console. To use it simply navigate to the directory where the python file is located and run the following command.
python generate_sonnet.py
A newly generated sonnet will then print out to your console. You may get a warning message from TensorFlow about CPU instructions but you can ignore that.
Colab Environment
 Colab environment that I used for this project. It contains all the necessary libraries and can easily be loaded.
1.	Open chrome or any other browser.
2.	Search for google-colab and open it.
3.	Upload file sonnet_generate in colab.
4.	Mount Google drive.
5.	Upload 
a.	datset.txt 
b.	model.h5
6.	Run code
After all setup, now you can run the code in the colab notebook. 

