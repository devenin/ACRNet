# Multilevel Feature Fusion Networks With Adaptive Channel Dimensionality Reduction for Remote Sensing Scene Classification

#### [Xin Wang](https://github.com/WangXin81) , [Lin Duan](https://github.com/devenin), Aiye Shi; Huiyu Zhou

Multilevel Feature Fusion Networks With Adaptive Channel Dimensionality Reduction for Remote Sensing Scene Classification[[Paper link\]](https://ieeexplore.ieee.org/document/9399658)

## Usage

1. Data preparation: `split.py`

```
dataset|——train
			|——Airport
			|——BareLand
			|——....
			|——Viaduct
	   |——val
			|——Airport
			|——BareLand
			|——....
			|——Viaduct
```



2. run `train.py` to train the model
3. `confusionmatrix.py` for drawing

## Environments

1. Ubuntu 16.04
2. cuda 10.0
3. pytorch 1.0.1
4. opencv 3.4

## Citation

Please cite our paper if you find the work useful:

```
@ARTICLE{9399658,
 author={Wang, Xin and Duan, Lin and Shi, Aiye and Zhou, Huiyu},
 journal={IEEE Geoscience and Remote Sensing Letters},
 title={Multilevel Feature Fusion Networks With Adaptive Channel Dimensionality Reduction for Remote Sensing Scene Classification},
 year={2021},
 volume={}, 
 number={}, 
 pages={1-5}, 
 doi={10.1109/LGRS.2021.3070016}}
```