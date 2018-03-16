# Action-Prediction-in-EgoCentric-Videos
Currently working
### Taking http://www.tamaraberg.com/papers/prediction.pdf "Temporal Perception and Prediction in Ego-Centric Video" as reference we have written code for Action Prediction 
#### save_data.m file computes the features from the Egocentric Videos and stores it in a matfile

#### D1.py trains the neural network with features extracted in save_data.m

#### D2.py finetunes the network trained in D1.py 


### Main Objective:
• The objective of this project is to predict what will happen next when a part of an  egocentric video of an activity is given.  
•Egocentric videos are captured by the camera mounted on the head or shoulder of a person i.e. first person videos.  
•The actions can be daily actions, sports actions ,etc.  
•Anticipating actions before they start or appear is a difficult problem in computer vision with several real-world applications.

### Work Done:
Implemented the paper “Temporal Perception and Prediction in Egocentric video” by Tamara Berg using MATLAB and Tensorflow.  
The dataset comprises of 5 action namely drinking water,putting on shoes,washing hands,putting on clothes and using the fridge captured from 5 subjects under different lighting conditions and locations.  
The model is trained for all those actions and the accuracy obtained is 66.7%.

### The tasks achieved are:
Snippet - A short part of the video typically of few seconds(here 2 secs).   
1.The first one is pair wise ordering scenario. In this task, they are given two short snippets from an egocentric video of an activity and asked to infer their correct temporal ordering.   
2.The second task evaluates the ability to make future predictions. Here a video showing part on an activity plus two
shorter snippets are provided and the model predicts which of the two snippets comes next temporally in the video.   



