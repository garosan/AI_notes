In an Anaconda Prompt:

- conda create --name tensorflow python=3.5
- activate tensorflow
- pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-1.0.1-cp35-cp35m-win_amd64.whl

To confirm TF is installed:

- python
- import tensorflow as tf

About environments:

- activate envname
- deactivate
- conda info --envs