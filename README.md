# cs480_kaggle_competition

Classify e-commerce products for cs480 kaggle competition. 

https://www.kaggle.com/competitions/uw-cs480-winter23/overview

Various techniques used, documented in notebooks.

- categorical.ipynb: uses categorical features (simple neural network).
- noisy-images.ipynb: uses noisy image data (CNN with dropout, batch normalization, and skip connections).
- noisy-text.ipynb: uses noisy text descriptions (transformer, treat input as bag of words).
- catboost.ipynb: combines previous three models (use catboost to perform gradient boosting).

bert and resnet models not used.
