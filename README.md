I used the Tensorflow and Keras frameworks to train and build a Convolutional Neural Network to classify images of disposed waste based on whether or not they are recyclable.
This model is a subcomponent of a smart recycling bin solution which is connected to a points-based rewards concept mobile application called LeafyTree which were designed to
promote sustainable living practices among all age groups.


### How the Proposed Smart Recycling Bin (Powered by the Model) Works
The user would place their disposables into the top holding compartment of the recycling bin which would take a picture and send them to the model that will be hosted on a cloud
platform. The model will classify them into two categories: Accepted (Plastic bottles, metal cans, cardboard etc.) and Rejected (Food waste). If the items placed are not recyclable,
they would be rejected by the CNN model and the user would be prompted by the smart recycling bin to remove the items. If the items placed are accepted by the CNN model, the smart
recycling bin would tally the weight of the items and reward points to the user's LeafyTree mobile account which they can then use to redeem rewards.
