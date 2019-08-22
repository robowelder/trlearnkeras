Transfer Learning with ResNet50

#Custom_data
#ResNet50 #Pretrained

Here, last layer of the pre trained model called ResNet50 in keras is custom with the another dataset from kaggle i.e dataset of cats and dogs.
Simply, freezing a layer of pre trained model to control weight which ultimately reduce the computational time without loosing accuracy of ResNet50 model.
We create the two layer --> 1st layer as the lumpsum weights from resnet50_weights_tf_dim_ordering_tf_kernels_notop.h5 and second layer as Dense for 2-class classification, i.e., dog or cat using SoftMax activation
