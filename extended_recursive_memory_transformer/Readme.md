# Vector TDAM 

Primary contact: tik11994@mail.ru

## Model objectives

This model is designed to analyze unlimitedly large vector images. Using it you can get vector representation of any vector image without limitation on their size.

## Example of work for a plagiarism search task

| Original image       | ![](test_image/orig/Щековая_дробилка_СМД-60А.png)    | ![](test_image/orig/Вальцы_смесительные.png)    | ![](test_image/orig/штука.png) |
|------------------|-------------------------------------------------------------|------------------------------------------------------------|------------------------------------------------------------|
| Plagiarism image | ![](test_image/plag/Щековая_дробилка_СМД-60А_plag.png) | ![](test_image/plag/Вальцы_смесительные_plag.png) | ![](test_image/plag/штука_plag.png) |

We present a new method for analyzing vector images that can process even large images such as drawings. The demonstrated examples show the ability of the model to search for similar images. 

## Usage
Clone the repository 
``git clone https://github.com/EgorBa/EvoVec-Evolutionary-Image-Vectorization``

### Dependencies 
Install dependencies by running
``pip install requirements.txt``

### Weights 
Download the model weights and place it in the folder model
[Download] (https://drive.google.com/file/d/1OTfNueVaXMzzgjd7mvheWYWUXHYUcMTM/view?usp=drive_link)
Place the data in the data folder

If you need to change the reading and writing paths of the results, you can do it by changing paths in the file config.ini

### Testing 
Run the code 
``python main.py``
