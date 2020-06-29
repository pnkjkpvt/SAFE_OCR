# SAFE_OCR

The image data and student database used in this project is closed source and is not provided in this repository. To get access to sample data you need to make a request [here](#).   
You can also use the skeletan image provide in `data` directory to create your own sample images, and fill up the CSV file with corresponding data along with random names and roll numbers for testing. You need to move your sample images in `data>images`. 

## Steps to run the project on google colaboratory.
1. First you need to ensure following directory structure in your google drive

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&boxvr;&boxh; My Drive  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&boxur;&boxh; `SAFE_OCR`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&boxur;&boxh; `data`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&boxur;&boxh; `models`  

2. (optional) Run **MNIST_model_training.ipynb** and **EMNIST_Model.ipynb** in google colab. This should save trained model in models>MNIST_Model directory and models>EMNIST_Model respectively. However, trained models are already provided in the repository.
3. Run **SAFE_OCR.ipynb** in google colab.
