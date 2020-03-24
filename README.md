
base nvidia/cuda:10.0-cudnn7-devel-ubuntu18.04

nvidia-docker run -it --rm --name mn -v /code:/code -e NVIDIA_VISIBLE_DEVICES=4,5 -p 8080:8080 sa2z/mrcnn:0.1

```
$ apt-get update

$ apt-get install python3 python3-pip git git-lfs
$ pip install --upgrade setuptools

$ echo "alias python='python3'" >> /etc/bash.bashrc
$ echo "alias pip='pip3'" >> /etc/bash.bashrc
$ source /etc/bash.bashrc
$ git clone https://github.com/sa2z/mrcnn.git
# check /home/mrcnn/pre-trained/ *.h5 files are existed

$ pip install -r requirements.txt
$ python setup.py install

```

