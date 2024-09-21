# Undergraduate Final Project- Skin Cancer

This is the code used to finish my undergraduate final project with the title "Skin Cancer Detection By Using Convolutional Neural Network". To train the model, I used data from [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T) 10,015 images were used to train the model and 1512 data to test the model. Due to the limited amount of data for skin lesion images, models were developed to classify two categories: cancer and non-cancer.

To use the model, transfer learning was used. I used pretrained model that is provided by Keras to classify ImageNet dataset. ResNet and DenseNet was chosen to classify the data. After training, I got DenseNet with 169 channel as the best model to classify the data with 79,82% accuracy, 79% Cancer Recall, and 80% Non-Cancer Recall.
