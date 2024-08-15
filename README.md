# Pose-Decompose




## Key idea: Pose Decomposition


## Installation instructions

``` bash
# 1. Create a conda virtual environment.
conda create -n dcn python=3.8 -y
conda activate dcn

# 2. Install PyTorch
conda install pytorch torchvision -c pytorch

# 3. Install mmpose
pip install mmpose
If you have problems installing mmpose, we recommend you to refer to the official tutorial: https://mmpose.readthedocs.io/en/latest/installation.html

# 4. Install PyTorch3D (Optional, only for visualization)
conda install -c fvcore -c iopath -c conda-forge fvcore iopath
conda install -c bottler nvidiacub
pip install git+ssh://git@github.com/facebookresearch/pytorch3d.git@stable

# 4. Pull our code
git clone https://xxxx
cd DCN

# 5. Install
pip install pycocotools
python setup.py develop  # or "pip install -e ."
```

Download necessary model files from [[Google Drive](https://drive.google.com/file/d/1un9yAGlGjDooPwlnwFpJrbGHRiLaBNzV/view?usp=sharing) | [Baidu](https://pan.baidu.com/s/1hVrUOt2QX_UTs4QuAgN2Lg?pwd=2u3c) (code: `2u3c`) ] and un-zip them in the `${ROOT}` directory.
