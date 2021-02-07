# Deep-Learning---CV-GANs-SSD-
Deep Learning - Computer Vision 



I was able to install pytorch and opencv individually after some google help. Here what I did.

1.updating the anaconda

conda update -n base -c defaults conda

2. creating the env

conda create --name XYZ

3. activate the env

conda activate XYZ

4.install pytorch < 0.4.0 (i installed 0.3.0)

conda install pytorch==1.1.0 torchvision==0.3.0 cudatoolkit=10.0 -c pytorch

5. install opencv

conda install -c conda-forge opencv

6. install opencv-python for dependency

pip install opencv-python
