# Car brand classification 🚙🚗🚘🚐
A simple web app that tells whether the uploaded image of a car is an :heart: Audi / Mercedes / Lamborghini ***(my dream car)*** :heart:

## Installation
Simply run the command: ***pip install -r requirements.txt***
This will take care of all the necessary dependencies.

## Usage:
1. Simply use [this](https://github.com/prateekralhan/Google-Images-downloader) script to download 5000 images of each of the 3 classes ***( Audi / Mercedes / Lamborghini )***.
2. Store them in a folder called **Datasets** into  separate folders as **train** and **test**. The directory structure should look something like this:

3. Execute and run the **Transfer Learning Inception v3.ipynb** to create and train your DL model. Instead of making one from scratch we used transfer learning here. 
I used [InceptionV3 architecture](https://arxiv.org/abs/1512.00567) as the main model.
4. Execute the command: ***python app.py***. This will launch the web-app in your browser. Enjoy!! 
