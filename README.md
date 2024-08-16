# Fire_RecognitionAI

Fire_RecognitionAI is an AI model that was developed to detect fire by ret-training the Resnet18 model using [this dataset](https://www.kaggle.com/datasets/kabilan03/fire-detection-dataset) from Kaggle. A few years ago, a fire was left unattended in my apartment building. Luckily, the sprinklers turned on and nobody was hurt. However, residents of the building needed to move so water damage could be addressed. By creating this AI model, I hope to minimize not just our cities, but nature too. Tens of thousands of wildfires occur each year, potentially, my AI model could give firefighters advance warning to save our planet.

Here is an image of my model successfully identifying a fire:![image](https://github.com/user-attachments/assets/21c7c2f3-b6bf-40b0-b1d9-85c32d8fa7e4)

Here is an image of my model successfully identifying a lack of fire:![image](https://github.com/user-attachments/assets/6043db53-3254-4a34-abd4-68ed22974a67)

## Algorithm

This program uses a pre-trained model using images from an existing dataset. The model was made with the Jetson Inference Library and uses the resnet18 network to process images. 

The model uses a recognition.py and a labels.txt to recognize and classify the images.

## Installation

This project requires Python and the Jetson Inference library to be installed on your system.

1. Clone the repository:
```sh
git clone https://github.com/MissionImpossible423/Fire_Recognition
```
2. Change directories into the repository folder:
```sh
cd Fire_Reconition
```
3. Run the python script:
```sh
python3 project.py path/to/image/here
```

## Here is a video demonstration of how the models works:

https://github.com/user-attachments/assets/b51c9b72-577e-4cb7-a5d1-c946358dca7b
