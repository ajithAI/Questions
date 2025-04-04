
# Questions

### Course 2 : Convolutional Neural Networks

### Week 1 : 
1. What are the Filters for Vertical Edge & Horizontal Edge Detectors ? 
2. Given Input shape & filter shape, what will be the output shape after convolution  ? O = ( I - F + 1) 
3. What will be the formula for Padding to get Input Shape = Output Shape ? ( P = ( F - 1 )  / 2 )
4. Valid = No Padding & Same Padding : Output Shape = Input Shape
5. Given Input shape & filter shape, what will be the output shape after convolution with Stride = S ? O = ( ( I - F ) / S ) + 1
6. Explain convolution operation of filter (3x3) on Input image (6x6) with mathematics & dimenssions.
7. Explain convolution operation of filter (3x3) on Input image (6x6) with Bias & Activation. 
8. Calculate number of parameters of a convolutional neural networks.
9. Calculate shape of output shape, given input shape, filter size, padding size & stride. ( ( ( I + 2P - F ) / S ) + 1 )
10. Describe Max Poolong & Avg Pooling along with Hyper parameters & Learnable Parameters.
11. Explain LeNet-5 at Highlevel. ( Input 32x32x1, 2x(Conv+Maxpool), 3xFC )
12. Why Convolution works ? Explain Parameter Sharing, Sparsity of Connections & Translation invarience.

### Week 2 : 
1. Explain LeNet-5 in detail.
2. Explain VGG-16 Network in detail.
3. Explain ResNet in detail. Why Resnet works better ?
4. Explain Inception Network in detail. Explain how 1x1 Conv layer can reduce computation costs.
5. Explain how Transfer Learning can be implemented & how it can be useful ? ( Pre-compute forzen layers ) 
6. Explain different Data Augmentation Techniques.
7. How to win Accuracy Benchmarks - Ensembling, Multi-Crop - Multi-Inference.

### Week 3: 
1. Difference between Localization vs Detection.
2. Explain Localization algorithm with Output & Loss function.
3. Explain Sliding Window Detection & explain why it is inefficient.
4. Explain Convolution implementation of sliding windows. ( Translation Invarience ) 
5. Explain IoU, Non-Max Supression.
6. How object in a image is assigned to grid cell and its anchor box.
7. Explain Yolo Algorithm in detail with all features.

