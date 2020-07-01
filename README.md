# CIE XYZ Net: Unprocessing Images for Low-Level Computer Vision Tasks
*[Mahmoud Afifi](https://sites.google.com/view/mafifi)*, *[Abdelrahman Abdelhamed](https://www.eecs.yorku.ca/~kamel/)*, *[Abdullah Abuolaim](https://sites.google.com/view/abdullah-abuolaim/)*, *[Abhijith Punnappurath](https://abhijithpunnappurath.github.io/)*, and  *[Michael S. Brown](http://www.cse.yorku.ca/~mbrown/)*
<br></br>York University

Reference code for the paper [CIE XYZ Net: Unprocessing Images for Low-Level Computer Vision Tasks](https://arxiv.org/pdf/2006.12709.pdf). Mahmoud Afifi, Abdelrahman Abdelhamed, Abdullah Abuolaim, Abhijith Punnappurath, and Michael S. Brown, arXiv preprint, 2020. If you use this code or our dataset, please cite our paper:
```
@article{CIEXYZNet,
  title={CIE XYZ Net: Unprocessing Images for Low-Level Computer Vision Tasks},
  author={Afifi, Mahmoud and Abdelhamed, Abdelrahman and Abuolaim, Abdullah and Punnappurath, Abhijith and Brown, Michael S},
  journal={arXiv preprint},
  pages={},
  year={2020}
}
```


## Code (MIT License)
![network_design](https://user-images.githubusercontent.com/37669469/81250194-550b1700-8fee-11ea-8a69-0fde90f1062f.jpg)

<!-- PyTorch -->

<p align="left">
  <img width = 20% src="https://user-images.githubusercontent.com/37669469/81490764-0c549780-9254-11ea-813c-02de8da42102.png">
</p>

#### Prerequisite
1. Python 3.6
2. opencv-python
3. pytorch (tested with 1.5.0)
4. torchvision (tested with 0.6.0)
5. cudatoolkit
6. tensorboard (optional)
7. numpy 
8. future
9. tqdm
10. matplotlib

##### The code may work with library versions other than the specified.

#### Get Started

#### Demos:
1. Run `demo_single_image.py` or `demo_images.py` to convert from sRGB to XYZ and back. You can change the task to run only one of the inverse or forward networks.
2. Run `demo_single_image_with_operators.py` or `demo_images_with_operators.py` to apply an operator(s) to the intermediate layers/images. The operator code should be located in the `pp_code` directory. You should change the code in `pp_code/postprocessing.py` with your operator code. 

#### Training Code:
Soon!

<br></br>

<!-- Matlab -->

<p align="left">
  <img width = 25% src="https://user-images.githubusercontent.com/37669469/81493516-e1c40800-926e-11ea-8685-11f41ade7ed4.png">
</p>

#### Prerequisite
1. Matlab 2019b or higher 
2. Deep Learning Toolbox

#### Get Started
Run `install_.m`. 

#### Demos:
1. Run `demo_single_image.m` or `demo_images.m` to convert from sRGB to XYZ and back. You can change the task to run only one of the inverse or forward networks.
2. Run `demo_single_image_with_operators.m` or `demo_images_with_operators.m` to apply an operator(s) to the intermediate layers/images. The operator code should be located in the `pp_code` directory. You should change the code in `pp_code/postprocessing.m` with your operator code. 

#### Training Code:
Soon!


<br></br>



## sRGB2XYZ Dataset
![srgb2xyz](https://user-images.githubusercontent.com/37669469/80854947-4eedf280-8c0a-11ea-8ada-e12bea63bdc6.jpg)

Download links will be available soon! 

