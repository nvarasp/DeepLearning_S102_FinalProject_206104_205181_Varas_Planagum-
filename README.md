# DeepLearning_S102_FinalProject_206104_205181_Varas_Planagum-
Repository for the final project of Deep Learning 2020.

LARGE-SCALE OBJECT CLASSIFICATIONS


The main objective is to build a neural network that is able to classify images of fruits into the corresponding type. 

We have used Fruit360 dataset but in a reduced way. The folder FinalProject contains all the needed data. 

The code can be found in code.ipynb.

We have tried 3 different models, obtaining accuracies between 87% and 97%.

Then we test some predictions.

Finally we wanted to try transfer learning in this project. 

Núria Varas Paneque -- U150389

Coral Planagumà Colom -- U149896

The presentation can be found in: https://docs.google.com/presentation/d/1izv-7wyc7Q-_E67LvJTV_ARxAUqkXGJXHx9x9_eB4YU/edit?usp=sharing

As a remark, we reduced considerably the quantity of the original dataset even though our project was large-scale classification because it was very demanding for our computers to run the code with those amounts for the three models and we were not able to use the cluster before the presentation. 

However, the models we created are able to classify the images into the corresponding classes given a much larger dataset. After the presentation we have been able to use the cluster and we have run the same code changing the number of classes to 25 (using a bigger dataset of 12k images for train and 4k for test) and we have obtained very good accuracies as well: 97.7% for the first model, 98.31% for the second and 96.8% for model 3. 

