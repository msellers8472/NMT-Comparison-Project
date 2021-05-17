# NMT-Comparison-Project
An experiment where I compare neural machine translation models for German to English, Italian to English, and French to English. I wanted to see whether German and English being closely related languages would translate to a German to English model being more accurate than a model translating Romance languages to English.

Note: This was written in Google Colab because I have a Mac and Google Colab allows me GPU capability.
I highly recommend running this notebook with GPU capability.
If you want to run this in Google Colab, then I would recommend uploading the data files and the notebook
to the same folder in Google Drive so that the program can run. If you are not running it in Google Colab,
then you may comment out these lines:

from google.colab import drive

drive.mount("/content/gdrive")

and replace the file paths in these lines:
german_path = '/content/gdrive/MyDrive/deu_short.txt'
italian_path = '/content/gdrive/MyDrive/ita_short.txt'
french_path = '/content/gdrive/MyDrive/fra_short.txt'

with wherever you are storing the data files.

This repository comes with smaller versions of the datasets because GitHub will not support larger files.
The full datasets can be found here: #http://www.manythings.org/anki/. You will want the datasets for German, Italian, and French. 

Many thanks go to my partner on this project, Rachael Dewey. 
