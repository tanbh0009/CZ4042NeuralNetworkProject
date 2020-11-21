# Material recognition CNN

The material data set used in the project is from the [Flickr Material Dataset (FMD)](https://people.csail.mit.edu/lavanya/fmd.html) and the [Materials in Context Database (MINC)](http://opensurfaces.cs.cornell.edu/publications/minc/)

## Version

TensorFlow version: 2.5.0-dev20201111

CUDA/cuDNN version:
cuDNN v8.0.4 for CUDA 11.0

GPU model and memory:
GeForce GTX 1070 graphics card
, RAM 16GB



## Setup image directory

```python
#Image dataset directory defined as follows:
# MINC dataset
data_dir = '../minc10'
# FMD dataset
data_dir = '../FMD/image'
```
Note: the MINC dataset used in this project only contains 10 classes: fabric, foliage, glass, leather, metal, paper, plastic, stone, water, and wood.
```
.
    ├── FMD
    │   └── image              
    │       ├── fabric
    │       ├── foliage
    │       ├── glass
    │       ├── leather
    │       ├── metal
    │       ├── paper
    │       ├── plastic
    │       ├── stone
    │       ├── water
    │       └── wood  
    ├── minc10
    │   ├── fabric
    │   ├── foliage
    │   ├── glass
    │   ├── leather
    │   ├── metal
    │   ├── paper
    │   ├── plastic
    │   ├── stone
    │   ├── water
    │   └── wood          
    │   
    └── src                    
        ├── Project_VGG16_FMD.ipynb              
        ├── Project_Xception_FMD.ipynb               
        ├── Project_VGG16_MINC.ipynb             
        └── Project_Xception_MINC.ipynb                             
```