# GMSA(Generalized Multi-Scale Approximation)
This project contains supplementary materials for our accepted paper 

Tao Li and Quanyan Zhu, On Convergence Rate of Adaptive Multiscale Value Function Approximation for Reinforcement Learning

2019 IEEE MLSP, Pittsburgh, PA, US. 

## Full Version Preprint
The skpipped proofs in the conference paper can be found in our preprint provided here, which later will also be available on arXiv. 

## Implementation
To implement our GMSA, please make sure that the followings are available
### Requirements
* Python 3.6
* Pytorch 
* CUDA 7.5 (GPUs)
* OpenAI gym (testbed)
* [wavelet packages](https://pywavelets.readthedocs.io/en/latest/regression/wp.html)   
In our experiment, only haar wavelets are involved hence no extra package is needed becasue of its simple structures. However, if more complicated basis functions come in, some wavelet packages are probably necessary (of course you can also devise the wavelets basis yourself)   

### A Tutorial
[Udacity](https://github.com/udacity/deep-reinforcement-learning/blob/master/tile-coding/Tile_Coding.ipynb) offers an example of classical tile coding, which is helpful for understanding the mechannism behind learning with adaptive basis. 

### GMSA 
The code will be available after we complete the modification according to the feedback from the workshop participants. 
