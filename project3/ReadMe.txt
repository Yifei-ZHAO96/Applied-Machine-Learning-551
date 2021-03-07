In this project, we implemented AlexNet, LeNet-5 and VGG model, and tested the influence of differenct optimizers and batchsizes on the performance of the model.
Specfically, this folder contains 7 .ipynb files:

1) AlexNet.ipynb: we trained a CNN model based on standard AlexNet for 87 epochs and achieved 95.8% accuracy on validation set and 95.12% on test set.
2) LeNet-5.ipynb: we made small modifications on the standard LeNet-5 model and trained the model for 51 epochs,  achieved 85.58% accuracy on validation set and 85.21% on test set.
3) VGG8.ipynb: based on standard VGG16 model, we reduced the number of layers to 8 and halve the number of kernels in each layer. This model helped us to achieve 97.6% accuracy on validation set and 97.4% on test set.
4) VGG9_2.ipynb: based on standard VGG16 model, we reduced the number of layers to 9 and halve the number of kernels in each layer. This model helped us to achieve 96.97% accuracy on validation set and 96.52% on test set.
5) optimizer.ipynb: we explored the influence of different optimizers (Adam, Adadelta, Adamax, RMSprop and SGD) on the performance of VGG model, and Adam proved to be the best optimizer in terms of vallidation accuracy and speed of convergency.
6) batchsize.ipynb: we explored the effect of different batchsizes (32, 64 128, 256) on the performance of VGG model.
7) ensemble.ipynb: to furtuer improve the performance of our model, we used ensemble method to combine models, we achieved 98.40% accuracy on validation set and 98.23% on test set.
 
After running each of these files, corresponding model file ('.h5') would be created in 'trained_models' folder and image of corresponding architecture of the model would be stored in 'figures' folder.