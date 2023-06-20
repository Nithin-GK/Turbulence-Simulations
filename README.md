# [ICIP '22] A comparison of different atmospheric turbulence simulation methods for image restoration

[Paper link](https://ieeexplore.ieee.org/abstract/document/9897969)

Atmospheric turbulence deteriorates the quality of images captured by long-range imaging systems by introducing blur and geometric distortions to the captured scene. This leads to a drastic drop in performance when computer vision algorithms like object/face recognition and detection are performed on these images. In recent years, various deep learning-based atmospheric turbulence mitigation methods have been proposed in the literature. These methods are often trained using synthetically generated images and tested on real-world images. Hence, the performance of these restoration methods depends on the type of simulation used for training the network. In this paper, we systematically evaluate the effectiveness of various turbulence simulation methods on image restoration. In particular, we evaluate the performance of two state-or-the-art restoration networks using six simulations methods on a real-world LRFID dataset consisting of face images degraded by turbulence. This paper will provide guidance to the researchers and practitioners working in this field to choose the suitable data generation models for training deep models for turbulence mitigation

### Link to pretrained models
 https://www.dropbox.com/sh/ndsfud9lq5m95nq/AAC1iUEICwDiF2z16qbhIIaza?dl=0
 
### Link to ATNet
https://github.com/rajeevyasarla/AT-Net

### Link to MPRNet
https://github.com/swz30/MPRNet 

### Link to Simulation method from "Turbulence-Induced 2D Correlated Image Distortion"

https://webee.technion.ac.il/~yoav/research/turbulence_distortion.html

### Link to Simulation method in "Simulating Anisoplanatic Turbulence by Sampling Inter-modal and Spatially Correlated Zernike Coefficients"

https://engineering.purdue.edu/ChanGroup/project_turbulence_TurbSim_v1.html

### Link to Simulation method from "Accelerating atmospheric turbulence simulation via learned phase-to-space transform"

https://github.com/Riponcs/TurbulenceSimulatorPython

Please cite the corresponding works if you utilize any of these simulators

### If you use our work, please use the following citation
```
@article{nair2022comparison,
  title={A comparison of different atmospheric turbulence simulation methods for image restoration},
  author={Nair, Nithin Gopalakrishnan and Mei, Kangfu and Patel, Vishal M},
  journal={arXiv preprint arXiv:2204.08974},
  year={2022}
}
```
