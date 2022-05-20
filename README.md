# Malaria-Image-Classfication
<p>The idea of this project is a prediction of classfication for Malaria cell images whether it is parasite or unifected.
A model were developed for predicting these images.</p>

## Folders & File Structure:
1) Folder Parasite: Image dataset for Malaria Parasite images.
2) Folder Uninfected: Image dataset for Malaria Uninfected images.
3) Augmentation_GenerateData.ipynb: Code file for generating new dataset for Parasite and Uninfected with Data Augmentation.
4) Malaria.ipynb: Code file for training the model. 

## Resources used
Python Version: 3.8.7
Data can be obtained from here: 
https://www.kaggle.com/datasets/meetnagadia/malaria-dataset

Libraries used in model training: Pathlib, Pandas, Matplotlib, cv2, Tensorflow, Keras, Sklearn, Eli5

## Methodology 
- Data Preparation
- Exploratory Data Analysis: Data Visualization
- Data Preprocessing
- Train Test Splitting: Ratio of 80% train and 20% testing
- Data Augmentation
- Optimized few Deep Learning approach: CNN, Transfer Learning(InceptionV3, VGG16) to reach the best model.
- Model evaluated with a few metrics(Accuracy, Precision, Recall and etc)
- ImagePrediction with Eli5

## Model Findings
### Accuracy:
| Model                             | Accuracy Score    | 
| -------------                     | -------------     |
| CNN(Deep Learning)                | 97.5%             |
| InceptionV3(Transfer Learning)    | 87.9%             |
| VGG16(Transfer Learning)          | 86.6%             |

### ROUCAUC Curve:
<img width="578" alt="image" src="https://user-images.githubusercontent.com/45889977/169439072-0acd0608-a573-4ef2-a939-bdce1abbe374.png">

