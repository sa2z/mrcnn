
base nvidia/cuda:10.0-cudnn7-devel-ubuntu18.04

```
$ apt-get update

$ apt-get install python3 python3-pip git

$ echo "alias python='python3'" >> /etc/bash.bashrc
$ echo "alias pip='pip3'" >> /etc/bash.bashrc
$ source /etc/bash.bashrc
$ git clone https://github.com/sa2z/mrcnn.git

$ pip install -r requirements.txt
```

