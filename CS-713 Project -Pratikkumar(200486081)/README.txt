To Run this Project.

I have used google colab.

Upload cyclegan_model.py and instancenormalization.py file in colab. and also zip folder of dataset
named monet2photo.zip

open cyclegan_monet2photo.ipynb file 

used below code for unzip dataset folder.

from zipfile import ZipFile
with ZipFile('/content/monet2photo.zip','r') as zip:
  zip.extractall('/content')

run cyclegan_model.py and instancenormalization.py files with following command:
!python /content/instancenormalization.py
!python /content/cyclegan_model.py

Below is link of google drive for my whole project folder.
https://drive.google.com/drive/folders/1-xMiGTprhhudbYwZUidlsXJ2JWx2HMYo?usp=drive_link