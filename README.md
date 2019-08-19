# Multi class image classification using Freiburg Groceries Dataset

The Freiburg Groceries Dataset consists of 5000 256x256 RGB images of 25 food classes.

![sample](grocery.png)

The paper can be found [here](https://arxiv.org/pdf/1611.05799.pdf) and the dataset [here](http://aisdatasets.informatik.uni-freiburg.de/freiburg_groceries_dataset).

## Environment and tools

1. Jupyter Notebook
2. Numpy
3. Pandas
4. Scikit-image
5. Matplotlib
6. Scikit-learn
7. Keras

## Network Architecture

_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
vgg16 (Model)                (None, 4, 4, 512)         14714688  
_________________________________________________________________
global_average_pooling2d_1 ( (None, 512)               0         
_________________________________________________________________
dropout_1 (Dropout)          (None, 512)               0         
_________________________________________________________________
dense_1 (Dense)              (None, 25)                12825     
=================================================================
Total params: 14,727,513
Trainable params: 12,825
Non-trainable params: 14,714,688
_________________________________________________________________

## Citing

```
@misc{Abhinav:2019,
  Author = {Abhinav Sagar},
  Title = {ICC 2019 WC Prediction},
  Year = {2019},
  Publisher = {GitHub},
  Journal = {GitHub repository},
  Howpublished = {\url{https://github.com/abhinavsagar/ICC-2019-WC-prediction}}
}
```





