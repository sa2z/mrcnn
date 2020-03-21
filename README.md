
base nvidia/cuda:10.0-cudnn7-devel-ubuntu18.04

```
$ apt-get update

$ apt-get install python3 python3-pip git
$ pip install --upgrade setuptools

$ echo "alias python='python3'" >> /etc/bash.bashrc
$ echo "alias pip='pip3'" >> /etc/bash.bashrc
$ source /etc/bash.bashrc
$ git clone https://github.com/sa2z/mrcnn.git
# check /home/mrcnn/pre-trained/ *.h5 files are existed

$ pip install -r requirements.txt
$ python setup.py install

```

