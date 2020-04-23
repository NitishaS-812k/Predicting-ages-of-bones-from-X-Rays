# Predicting-ages-of-bones-from-X-Rays
This notebook explore the dataset used in the Pediatric Bone Age Challenge, 2017, also known as the RSNA(Radiological Society of North America) and attempts to predict the ages of children using X-Ray images of their hands.More information about the dataset and the dataset itself can be found on kaggle <a href = 'https://www.kaggle.com/kmader/rsna-bone-age'>here.</a><br>
## Model description
The notebook uses the pre-trained model Xception to predict ages. I have used the ImageDataGenerator class to load this enormous dataset into memory efficiently, to preprocess the images and to augment the dataset. Visualisations to explore the data and the evaluation results are included in the notebook. The notebook obtained a mean absolute error of approximately 12.7 months.<br>
## Requirements
<ul>
  <li> <b>Tensorflow:</b> To use Xception and related functions for training and preprocessing( keras is included in tensorflow)</li>
  <li><b> Numpy:</b> For computation on the dataset</li> 
  <li><b> Pandas:</b> To load csv files and plot data</li>
  <li><b> Matplotlib:</b> For creating visualisations</li>
  <li><b> Seaborn:</b> For creating visualisations</li>
  <li><b>Sklearn:</b> To split data into training and validation</li>
  </ul>
  
## Improvements possible
InceptionResNetV2 might perform slightly better but it wasn't possible to train it because of the large size of its weights.There are many combinations possible by using different models, optimizers and learning rates.<br><br>
The same notebook is available on kaggle <a href = 'https://www.kaggle.com/daenys2000/bone-age-prediction'>here.</a>
