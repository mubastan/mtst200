# mtst200
Mobile Turkish Scene Text dataset (MTST 200)

The dataset contaıns 200 jpg images (1.jpg, 2.jpg,...,200.jpg) recorded with mobile phones and resized to 1024x576 or 576x1024 pixels.

The image files are in zip archives images1.zip, images2.zip, images3.zip (had to be partitioned due to upload size limitation).

The ground truth bounding box annotations are in labels.zip, containing 1.jpg.labels.txt, 2.jpg.labels.txt, ..., 200.jpg.labels.txt  one txt file for each image. The dataset was annotated with the scene text annotation tool (STAT) available at https://github.com/mubastan/stat

The format of the annotation files is as follows:

imageFileName

boundingBox(left,top,width,height) textLabel

Example: 2.jpg.labels.txt

2.jpg

0 130 218 275 61 Öğrenci İşleri

1 224 281 98 45 Ofisi

2 126 328 276 40 Student Affsirs Office

One can use STAT (https://github.com/mubastan/stat) to load and refine/correct these annotations.

# References:

M. Bastan, H. Kandemir, B. Cantürk, "MT3S: Mobile Turkish Scene Text-to-Speech System for the Visually Impaired", arXiv:1608.05054, August 2016.

