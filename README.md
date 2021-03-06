
--------------------------------------------------------------------------------
[![image](https://img.shields.io/pypi/l/requests.svg)](https://github.com/ElecRex/Manifold-Learning-Algorithms)
![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)
## Requirements
* NumPy 1.16.3
* scikit-learn 0.21.2
* Matplotlib 3.1.0
* Python 3.7

## Usage
### the dataset of Data
(Determine if the man in the image has a beard)
```
├── Data
       ├── train
           ├── s1.bmp 
           ├── s2.bmp
           └── ...
       ├── test (The last 10 images of Data)
           ├── s101.bmp 
           ├── s102.bmp
           └── ...
       ├── labels.txt (For attribute information) 
```


## Summary
![overview](./assets/Manifold_2D_Updated2.png)

## Results 
### MDS (Multidimensional Scaling)
![mds](./assets/MDS_3D.png)

### Isomap (Isometric Feature Mapping)
![isomap](./assets/Isonmap_3D.png)

### LLE (Locally Linear Embedding)
![lle](./assets/LLE_3D.png)

### LE (Laplacian Eigenmaps)
![isomap](./assets/LE_3D.png)

## Reference
* [NumPy-Document](https://www.numpy.org/devdocs/reference/index.html)
* [scikit-learn-Document](https://scikit-learn.org/stable/_downloads/scikit-learn-docs.pdf)
* [Matplotlib-Document](https://matplotlib.org/3.1.0/users/index.html)

## Author
- written by **xzj** @ 2019-6-14

 

