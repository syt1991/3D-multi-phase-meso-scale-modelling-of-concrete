If useful to your research, we would appreciate a citation:<br>
***Yutai Su, Percy M. Iyela, Jiaqi Zhu, Xujiang Chao, Shaobo Kang, Xu Long. 
"A Voronoi-based gaussian smoothing algorithm for efficiently generating RVEs of multi-phase composites with graded aggregates and random pores." 
Materials & Design (2024): 244, 113159.***<br>
Feel free to utilize this code. 
If any questions, please email us (suyutai@nwpu.edu.cn). <br>


# 3D-multi-phase-meso-scale-modelling-of-concrete
## Keywords:
Abaqus; Python script; Mayavi; three-dimensional (3D) meso-scale model; multi-phase material

## Introduction
I'd like to share some codes from my research and hope it helps. <br>
An numerical modeling framework was proposed to generate highly realistic 3D mesoscale multi-phase concrete models with unprecedented efficiency and accuracy. <br>
Our framework achieved a significant wide range in aggregate volume fraction (0 to 80%) and featuring rapid model generation capabilities, 
and extemely reduce computational time—achieving simulations of 1 million elements within mere 30 s on readily available hardware. <br>
## Packages requirements
Packages, including numpy, scipy, and mayavi are needed.
Inp files with ordered element numbers in Abaqus should also be prepared first. <br>
## Coding
See main.py file.<br>
## Some results
Mesostructure of our model: <br>
![image](https://user-images.githubusercontent.com/116877222/221400622-1f44794d-f6b7-474f-8b96-abc23ccf35f2.png)<br>
Generation time for 1,000,000 elements:<br>
![image](https://user-images.githubusercontent.com/116877222/221400646-3b096761-83ba-49ca-a6a2-b2f1bf4e5da8.png)<br>
