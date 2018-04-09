 U_Net model is used for segmenting skin cancer images (resized to 256 * 256). 

Clasification:
  Three differet models are used. 1) Simple model with 4 convolutional layers and a FCN layer, 2) VGG16 and 3)resnext. Out of these three the simple model gave better precisoon and recall values when trained with class weights.
