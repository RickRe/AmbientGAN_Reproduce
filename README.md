# AmbientGAN_Reproduce
This repository provides code to reproduce results from the paper AmbientGAN: Generative models from lossy measurements.
This repository is a work under COMP6248 Reproducability Challenge. The code has referred to #https://github.com/AshishBora/ambient-gan and #https://github.com/shinseung428/ambientGAN_TF/blob/master/ambientGAN.py


    Requirements:
    Python 3.7
    Tensorflow >= 1.4.0
    matplotlib
    scipy
    numpy
    cvxpy
    scikit-learn
    tqdm
    opencv-python
    pandas
    
    Test dataset:
    Mnist
    CelebA
    
    Run: train is the main file
    Load the whole folder
    change the data path in ops.py
    run train
    Mnist result
![image](https://github.com/chickenshawama/AmbientGAN_COMP6248-Reproducability-Challenge/blob/master/images/p1.png)
    block pixel probability=0.5
![image](https://github.com/chickenshawama/AmbientGAN_COMP6248-Reproducability-Challenge/blob/master/images/p2.png)
    hybrid measurement
