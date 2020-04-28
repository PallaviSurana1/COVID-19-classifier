# COVID-19-classifier

### Classification of COVID-19 infection in pulmonary images using Transfer learning approach
In this project, the aim is to use transfer learning to predict the infection of COVID-19 using chest X-Rays as the input.

#### Transfer learning task
The idea is to take a network which is pre-trained on a different domain from the task of interest, in this case the ImageNet database. Followed by, adapting it to your task. Deep learning is a representative of inductive learning where the objective for inductive-learning algorithms is to infer a mapping from a set of training examples. 

A VGG16 and VGG19 model is trained for this prediction task. The database used is from Kaggle, "COVID-19 Radiography Database", that contains images of COVID-19, Viral pneumonia and Normal Chest X-rays. Thsi project aims to classify lung images as COVID-positive or negative (2 classes). 

###### URL to the database - https://www.kaggle.com/tawsifurrahman/covid19-radiography-database

#### Detailed experiment
COVID_VGG16.ipynb and COVID_VGG19.ipynb contain the detailed experiment and are under vgg-16 and vgg-19 branches respectively. For visualisation of results the Accuracy and error plots are considered that is under the images branch.
The overall accuracy is > 95% and other results are included in the .txt files in the respective branches of the models.

The current study showed approx a 7-10% of misclassification and the images are enlisted in the images branch. Transfer learning is the start point to build CNN's for such applications. There are other models that might perform better than the ones considered and have been worked on in other studies like Resnet, Inception, and others.

#### Future experiments and limitations
This is an effort to show how transfer learning can be used in a situation where the demand to reach the diagnosis of a patient is very sensitive and high. Further innovation and bettering the models using different models and picking the best one would help in applications in the healthcare industry. Further, chest CT images are preferred over XRays as they have a better readout and studies have shown they are more effective in their approach to classify between COVID+ patients and otehrwise. 
