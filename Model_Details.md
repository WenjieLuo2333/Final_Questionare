Unet Model are used as basic structures[MIT License].
Basic Unet Models are forked from public-shared Kernel on Kaggle.
And then we modified the network.
Layers Used: Convolution Layer, Dropout, Batch Norm, Activation(Relu), add(shortcut in resnet)
loss function: binary_crossentropy
metrics: [accuracy (IOU)](https://www.kaggle.com/aglotero/another-iou-metric)

I chose this model because it's a common used image segmentation network and nearly all the public shared Kaggle Kernels are based on Unet which proved that it's good for this competition.

Also normal networks are tried, and Resnet Models with bottle-neck structure are tried, these structure work not that good in this case.

We also tried to change the size of the filters, change the dropout ratio and learning strategies. And finally we kept the best one.

