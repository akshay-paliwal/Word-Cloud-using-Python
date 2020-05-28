# Project Title
Word Cloud using Pytohn

## Introduction
This is my final project in Crash Course on Python. For this project, the code was written to created a **wordcloud** from a text by writing a script. This code needs to process the text, remove punctuation, ignore case and words that do not contain all alphabets, count the frequencies, and ignore uninteresting or irrelevant words.

A *Wordcloud* is a visual representation of text data. It displays a list of words, the importance of each beeing shown with font size or color. This format is useful for quickly perceiving the most prominent terms. Python is totally adapted to draw this kind of representation, thanks to the wordcloud library.

## Install
This project requires **Python 3**. Also, soame of the python libraries like matplotlib, wordcloud, fileupload, numpy and PIL.

Installed [Anaconda](https://www.anaconda.com/products/individual), a pre-packaged Python distribution that contains most of the necessary libraries and software for this project. To check for the existing libraries and download missing libraries following code is used...
```
!pip install wordcloud
!pip install fileupload
!pip install ipywidgets
!jupyter nbextension install --py --user fileupload
!jupyter nbextension enable --py fileupload

import wordcloud
import numpy as np
from matplotlib import pyplot as plt
from IPython.display import display
import fileupload
import io
import sys
```

## Code
* ``` Step- 1``` Upload the text file and calculate the frequency of relevant words and save it in a dictionary.
* ``` Step- 2``` Create pixel array from the mask image.
* ``` Step- 3``` Create the wordcloud from the dictionary. Set the background color, mask, etc.
* ``` Step- 4``` Display the generated image.

## Data
The data consists of a text file (with large number of words) like a book, wikipedia page, etc.
