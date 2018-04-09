Used U_Net model for segmenting skin cancer images (resized to 256 * 256). 

Clasification:
  Used three differet models simple model with 4 conv layers and a fcn layer, VGG16 and resnext.
  Out of these three the simple model gave better precisoon and recall values when trained with class weights.
