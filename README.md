# Image Captioning including Attention

The product is designed for the blind people, who cannot see the pictures but can listen to the description. We are aiming to enable blind people to access more information and experience the beauty of the world. Our product can predict the captioning of a image and display in the frontend. User can upload a image and play the audio of the captioning of the image, so that the blind can "hear" the image. 

The default frontend looks like
![image](https://user-images.githubusercontent.com/97444802/163241489-7ab169b6-2865-4668-be47-a5827a145a47.png)
When you upload a image, it shows like 
![image](https://user-images.githubusercontent.com/97444802/163241619-63c6b4dd-8755-4f1a-83db-29dfb064da6d.png)

## Dataset

[Flickr8k dataset from Kaggle](https://www.kaggle.com/datasets/adityajn105/flickr8k)

## Deploy
![Untitled Diagram drawio (2)](https://user-images.githubusercontent.com/76429734/163243232-b42f427c-b470-4a05-81a1-8e6b2b5f3e08.png)


## Getting started in the local machine:

1. Clone this repo
2. Download the "Image" folder and captions.txt from the above dataset and put them in a new "flickr8k" folder within the repo directory
3. Download [my trained model](https://drive.google.com/file/d/1t3QbSauxSnZhXE1DbuGwiT2AokOsqOjA/view?usp=sharing) and put it in a new "models" folder within the repo directory
4. pip install -r requirements.txt
5. Open Python Shell and run:
    import spacy
    
    from spacy.cli.download import download
    download(model="en_core_web_sm")
6. Run app.py


## Getting started in Colab:

[![My Colab notebook](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1z1sI5wVmoflOggLfIuIIj7qQ0xAICtgn?usp=sharing) 

Download the Image folder and captions.txt from the above dataset, zip the "Image" folder and put it in the Colab working directory with captions.txt
