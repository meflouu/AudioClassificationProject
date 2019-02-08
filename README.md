# AudioClassificationProject

## Task
Investigate the techniques behind audio classification and build a neural network model that performs a supervised classification. 
For this lab we choose to go for the subdomain of audio classification of the environment sounds. That’s why we picked the dataset UrbanSound8K. It offers sound segments sliced to at 4 seconds maximum.
Implementation was done in Python using Keras library that abstracts on top of TensorFlow. Conda virtual environment was used to run jupyter-notebook that will help to visualize each step and what was achieved.


## Dataset
Urban8k dataset contains 8732 labeled sound excerpts, each of them is less than 4 seconds long. All sounds are from an urban environment and in total there are ten classes, labeled from 0 to 9:
0. air_conditioner  
1. car_horn  
2. children_playing  
3. dog_bark  
4. drilling  
5. engine_idling
6. gun_shot
7. jackhammer
8. siren
9. street_music

