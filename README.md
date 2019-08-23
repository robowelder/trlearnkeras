# Transfer Learning with ResNet50 in Keras

## Custom_data, ResNet50 ,Pretrained

**Transfer learning,** is a research problem in machine learning that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem.In general, there are two types of transfer learning in the context of deep learning:

1. Transfer learning via feature extraction
2. Transfer learning via fine-tuning
The notebook called **Transfer learning** is intended to be a tutorial on Keras around image files handling for **Transfer Learning using pre-trained weights from ResNet50 convnet.**
Here, last layer of the pre trained model called **ResNet50 in keras is custom with the another dataset from kaggle** i.e dataset of cats and dogs.Simply, **freezing** a layer of pre trained model to control weight which ultimately reduce the computational time without loosing accuracy of ResNet50 model.
We create the two layer,1st layer as the weights from **resnet50_weights_tf_dim_ordering_tf_kernels_notop.h5** and second layer as **Dense for 2-class classification**, i.e., dog or cat using **SoftMax activation**

[Concept of Transfer Learning ](https://www.youtube.com/watch?v=L7qjQu2ry2Q)


1. First Download the [ResNet50 Dataset ](https://www.google.com) .You can also download it from kaggle or any other open source.
2. Next download another dataset, I have choosen as cats and dogs dataset.You can custom your own dataset here.
[Cat and Dog train-valid dataset ](https://www.google.com) and
[Test dataset ](https://www.google.com)

With all above steps through the transfer learning nookbook, import the useful library and run your model.
