# Multi class object classification using Freiburg Groceries Dataset

Unofficial code for paper "A Hierarchical Grocery Store Image Dataset with Visual and Semantic Labels"

## If this repository helps you in anyway, show your love :heart: by putting a :star: on this project :v:

Check out the corresponding medium blog post [https://towardsdatascience.com/multi-class-object-classification-for-retail-products-aa4ecaaaa096](https://towardsdatascience.com/multi-class-object-classification-for-retail-products-aa4ecaaaa096).

The Freiburg Groceries Dataset consists of 5000 256x256 RGB images of 25 food classes. I have used Transfer Learning using pre trained 
VGG weights to make a model for multi class image classification. It can be of great use in automatic image
classification to help a food and groceries retailer reduce human effort in the inventory management process of its warehouse and retail 
outlets.

The paper can be found [here](https://arxiv.org/pdf/1611.05799.pdf) and the dataset [here](http://aisdatasets.informatik.uni-freiburg.de/freiburg_groceries_dataset). The full dataset is provided in this repository for convenience.

![sample](grocery.png)

## Environment and tools

1. Jupyter Notebook
2. Numpy
3. Pandas
4. Scikit-image
5. Matplotlib
6. Scikit-learn
7. Keras

## Installation

`pip install numpy pandas scikit-image matplotlib scikit-learn keras`

`jupyter notebook`

## Results

### Loss/Accuracy vs Epoch

![loss/accuracy](results.png)

### ROC-AUC curve

![roc-auc](grocery2.png)

### Correct/Incorrect classification samples

![results](grocery3.png)

The model is able to reach a validation accuracy of 60% which is quite good considering the number of classes(25) with 100-200 images in each category. Feel free to use different architectures and play with the hyperparameters for better results.

## Citing

```
@misc{Abhinav:2019,
  Author = {Abhinav Sagar},
  Title = {Grocery Image Classification},
  Year = {2019},
  Publisher = {GitHub},
  Journal = {GitHub repository},
  Howpublished = {\url{https://github.com/abhinavsagar/Grocery-Image-Classification}}
}
```




