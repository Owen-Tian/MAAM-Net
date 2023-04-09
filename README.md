# MAAM-NET
 
This is the source code of MAAM-Net.

This repo includes:

    CKPT - checkpoint among three datasets;
    *.py - codes.
    
The dataset should be like:

	~/** dataset/training(testing)/01_111/001.jpg
    ~/** dataset/training_flow(testing_flow)/01_111/001.flo

To train the model, run with:

    python train.py
    
To test the model, run with:

    python test.py
    
Look the detail hypermeters in the train(test).py...  

-----------------------------------------------------------------

The environment requirements are as follows:

absl-py              0.9.0
astor                0.8.1    
certifi              2020.6.20
channelnorm-cuda     0.0.0    
correlation-cuda     0.0.0    
cycler               0.10.0   
decorator            4.4.2    
gast                 0.4.0    
grpcio               1.31.0   
h5py                 2.10.0   
imageio              2.9.0    
importlib-metadata   1.7.0    
joblib               0.16.0   
Keras-Applications   1.0.8    
Keras-Preprocessing  1.1.2
kiwisolver           1.2.0
Markdown             3.2.2
matplotlib           3.3.1
mock                 4.0.2
networkx             2.4
numpy                1.19.1
opencv-python        4.4.0.42
Pillow               7.2.0
pip                  20.2.2
protobuf             3.13.0
pyparsing            2.4.7
pypng                0.0.21
python-dateutil      2.8.1
PyWavelets           1.1.1
resample2d-cuda      0.0.0
scikit-image         0.17.2
scikit-learn         0.23.2
scipy                1.5.2
setuptools           49.6.0.post20200814
six                  1.15.0
sklearn              0.0
tensorboard          1.13.1
tensorflow-estimator 1.13.0
tensorflow-gpu       1.13.1
termcolor            1.1.0
threadpoolctl        2.1.0
tifffile             2020.8.13
Werkzeug             1.0.1
wheel                0.34.2
zipp                 3.1.0
