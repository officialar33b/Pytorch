# MNIST Classification
The aim is to classify handwritten digits of color black and white into labels from 1 to 9.

<img alt='handwritten digits' srcset="https://bytepawn.com/images/mnist-example.png">

## Requirements: 
[requirements.txt](./requirements.txt)

## Model:
Input image size: **(1,28,28)**

```
----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1           [-1, 10, 24, 24]             260
            Conv2d-2             [-1, 20, 8, 8]           5,020
            Linear-3                   [-1, 50]          16,050
           Dropout-4                   [-1, 50]               0
            Linear-5                   [-1, 10]             510
================================================================
Total params: 21,840
Trainable params: 21,840
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.00
Forward/backward pass size (MB): 0.05
Params size (MB): 0.08
Estimated Total Size (MB): 0.14
----------------------------------------------------------------
```