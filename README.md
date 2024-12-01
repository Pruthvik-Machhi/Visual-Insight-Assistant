# Food Insight Assistant

## Introduction  

Many people face challenges in recognizing food items, especially those who are visually impaired. Additionally, not knowing the nutritional value of the food we eat can make it harder to make healthy choices. Some foods might also pose health risks if we are unaware of their effects.  

This project aims to address these issues by developing a system that can identify food items from images. Once the food is identified, the system will provide useful insights, such as nutritional information and dietary recommendations.

## Features  

1. **Food Classification**  
2. **Calories & Protein Level**  
3. **Suggestions**  
4. **Health Alerts**
   
## Dataset  

1. **Image Collection**  
   - Collected **117 images**, which were expanded to **553 images** after cropping.   
   - Added **150-200 similar images** for each category to improve diversity and robustness of the dataset.  

2. **Nutrition Data**  
   - Collected detailed nutritional information for each category, including:  
     1. **Calories**  
     2. **Protein Content**  
     3. **Dietary Suggestions**
  
## Preprocessing  

1. **Image Resizing**  
   - Resized all images to a fixed size to ensure uniformity and compatibility with the model.  

2. **Data Augmentation**  
   - Applied augmentation techniques during the training process to improve model generalization:  
     - **Cropping**  
     - **Flipping**  
     - **Rotation**  
     - **Scaling**  

3. **Normalization**  
   - Normalized pixel values to a range of **0 to 1** for consistent input to the model.
  
## Model  

The food classification system was built using a **scratch-designed Convolutional Neural Network (CNN)**. This custom model was designed and implemented from the ground up to effectively process and classify image data. By stacking convolutional, pooling, and fully connected layers, the model learns spatial and feature hierarchies from the input images.  

The scratch-built CNN was trained on the preprocessed dataset and optimized for accurate classification of food items for each categories.

### CNN version 1

### CNN version 2
### CNN version 3
### CNN version 4





