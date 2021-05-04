# melanoma_detection
Use CNN model to classify 'melanoma', 'nevus', 'seborrheic_keratosis  

Dataset:   
The dataset is from the 2017 ISIC Challenge on Skin Lesion Analysis Towards Melanoma Detection.  

The contents in this code:
1. Preprocess the image data before training. Make the dataloader.  
3. Use pretrained model vgg16 to do transfer learning.  
4. Design the training process. 
5. Output the prediction scores of three class in the csv file.  

The model performance:  
Test accuracy: 70% after 42 epochs training.  
![ROC curve](https://github.com/CarlEarth/melanoma_detection/blob/main/images/ROC_curves.png)  
![Confusion matrix](https://github.com/CarlEarth/melanoma_detection/blob/main/images/Confusion_matrix.png)  
