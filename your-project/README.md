<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Guess who?
*Marta Palleiro*

*Data Analytics, Barcelona 2020*

## Content
- [Project Description](#project-description)
- [Questions](#hypotheses-questions)
- [Dataset](#dataset)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion and future work](#conclusion)
- [Organization](#organization)
- [Links](#links)

## Project Description
Through the application of deep-learning techniques I have trained an algorithm capable of identifying some of the 50 most influential artists of all time. The main goal is to recognise as many artist and paintings as possible.

## Questions
Imagine that you are in front of a painting and you have no idea about it but you want to understand what you are looking at. Who is the author of this painting? When was it painted? Which movement the author of the painting belongs? or what is the story of this painting?

## Dataset
I have selected a dataset from [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time) about the 50 most influential artists in art history. It contains a collection of images of the paintings and information retrieved from wikipedia in CSV format.

## Model Training and Evaluation
I have tested a basic CNN model and the VGG-16 model with two artists to compare the results of the accuracy. The result of the accuracy with the VGG-16 model was higher so I trained this model with 4 artists (Vicent van Gogh, Edgar Degas, Pablo Picasso and Paul Gauguin).

## Conclusions and future work
I have obtained an accuracy of around 80% which it is a good result! 
In the future I would like to improve the accuracy adding more paintings to the dataset and using data augmentation. Also, I should try to indetify more information about the paintings, not only the author.

## Organization
First of all, I researched about the topic and looked for a database. Then, I studied what kind of algotirthms could work best and started training the VGG-16 model and tested it with 4 artists. Due to storage issues, the trained models cannot be uploaded to Github. 

## Links

[Repository](https://github.com/martapalleiro/Project-Week-8-Final-Project)  
[Slides](https://www.canva.com/design/DAEFV3yUbe8/Sor5p54u7_Qcybuc9qnh2g/view?utm_content=DAEFV3yUbe8&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)    
