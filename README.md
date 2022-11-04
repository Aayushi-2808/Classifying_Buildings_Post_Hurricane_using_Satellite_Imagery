## Classifying_Buildings_Post_Hurricane_using_Satellite_Imagery
# Introduction
> Hurricanes are large, spiraling tropical storms that can pack wind speeds of over 160 mph and unleash more than 2.4 trillion gallons of rain a day.
> Between 1980 and 2021, hurricanes have caused damage over $1.1 trillion, with an average cost of $20.5 billion per event.
> They are responsible for the highest number of deaths among all natural disasters: 6,697 between 1980 and 2021.
> The deadliest hurricane on record was a Category 4 storm that hit the island city of Galveston, Texas.

# Objective
> After a hurricane, damage assessment is vital for relief workers and first responders so that resources and assistance can be appropriately planned and allocated.
> In this project,  we are trying to classify damaged and undamaged buildings using the satellite imagery data.


# Flow of project is as explained below:
This project is divided into 4 parts:
1. Exploratory Data Analysis      
2. Modeling
> - Baseline ANN
> - CNN with Regularisation
> - SotA with Transfer Learning (ResNet50)    
3. Inferences
> - Saliency Maps
> - Model Comparison
4. Conclusion and Future Work

# Refer below for References:
1.   https://arxiv.org/abs/2111.14650
2.   https://arxiv.org/abs/1512.03385

# Results
> Based on the performance metrics, the ResNet50 model with ImageNet weights outperforms the ANN model by a significant margin and the CNN model by a small margin on both the balanced and imbalanced testing datasets.
> However, there seems to be a minor loss in Precision when dealing with Imbalanced data for all the models.

# Future Works

> In future, we can expand the scope of this model by using object segmentation and detection to detect buildings and then perform classification of the buildings, post any natural disaster.
> We can also try to predict the magnitude of damage for each building so that buildings which suffered more damage are prioritized to be assisted first.




