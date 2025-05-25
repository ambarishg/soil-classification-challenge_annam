# Challenge 1:
Pretrained Models with custom heads have been used with 5-fold cross validation and image size of 512
Models used are 
* resnext50_32x4d           
* EfficientnetB3          
* EfficientnetB5            
* EfficientnetB7               
* Vision Transformer Patch 16 384         

| Notebook Name | Description |
|----------|----------
| soil-02-EFFNETB3    | Notebook for the EFFNETB3 classification training    |
| soil-02-EFFNETB5    | Notebook for the EFFNETB5 classification  training  |
| soil-02-EFFNETB7    | Notebook for the EFFNETB7 classification  training   |  
| soil-02-vit   | Notebook for the VIT classification  training   |   


# Challenge 2:         

We follow a autoencoder architecture to  train the images 

The anomalies are detected using the reconstruction error  

Top 5% are counted as anomalies        

Backbone used
EfficientnetB0 , EfficientnetB1 ,EfficientnetB3 , EfficientnetB5
Simple Auto Encoder  


| Notebook Name | Description |
|----------|----------
| soil-comp02-effnetb1    | Notebook for the EFFNETB1 autoencoder training    |
| soil-comp02-effnetb3    | Notebook for the EFFNETB3 autoencoder training    |
| soil-comp02-effnetb5    | Notebook for the EFFNETB5 autoencoder training       |  
|soil-comp02-simple-autoencoder   | Notebook for the Simple Autoencoder  training   |

