# MultiClass-Traffic-Signs-Classifier
# Computational Intelligence - Systems Inspired by Biology Project

#

# Summary
The aim of this project is to develop a Multiclass Image Classification model for traffic signs label recognition. A dataset consisting of 1792 images belonging to 20 different traffic sign classes was used as the training dataset, while a similar dataset consisting of 1022 images was used for testing purposes.
![image](https://github.com/eceauthgroup/MultiClass-Traffic-Signs-Classifier/assets/25185757/6ad0001c-dd7c-40f7-9755-e1082ba6972e)

# Conclusions
The Inception V3 pre-trained network was used for this project, as its preliminary analysis provided the best results in terms of accuracy and execution time. When dealing with computation intelligence problems, execution time may not be such a crucial factor, but due to extensive training it was taken into account.

# Better results

-> Increase the size of the training dataset. This can be accomplished by using more images or by experimenting with different augmentation techniques.

-> Remove the EarlyStopping callback and train the model for more epochs. EarlyStopping helps to prevent overfitting, however it may lead to worse results when dealing with small datasets.
