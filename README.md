# Melanoma-Assignment

**Problem statement:** To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

# The Proposed Solution will follow below 8 steps:
- **Step 1** - Importing all the important libraries
- **Step 2** - Load and extract the Skin Caner dataset to google drive
- **Step 3** - Create Test and Validation dataset
- **Step 4** - Visualize the data and images
- **Step 5** - Model Builing for the provided dataset
- **Step 6** - Application Basic Data Augumentaion Strategy
- **Step 7** - Find the distribution of classes in the training dataset
- **Step 8** - Rectify the class imbalance and build model again

# Final Observations 
1. The original provided dataset doesn't contain enough images to train neural network like CNN. 
2. The train and Validation accuracy are low with the original dataset.
3. The trained model with original dataset has shown signs of overfitting.
4. Adding a single data augumentation layer didn't help much
5. Generating new images using tool Augmentor has help improving the accuracy.
6. The final model train accuracy of model is approx 90% (When trained with 1000 addition images of each class)
7. The final model validation accuracy of model is approx 90% (When trained with 1000 addition images of each class)
8. Data augimetation also help in catering overfitting. 
