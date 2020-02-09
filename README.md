# pytorch-samples
a few pytorch implementation samples

## prerequisite
### 1. Python环境管理工具
首先需要明确开发和学习环境要求，这里以anaconda作为python package管理工具

首先下载anaconda安装包，这里推荐Anaconda3-5.3.0版本，国内tuna源高速下载地址为:https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/

安装后请按照https://mirrors.tuna.tsinghua.edu.cn/help/anaconda/ 设置`.condarc` 文件中Anaconda 仓库与第三方源

### 2. Python环境配置
本repo采用python 3.6 和 pytorch 1.4 (cpu version),配置命令语句如下:
``` cmd
$ conda create -n pytorch python=3.6
$ pip install pip -U
$ pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
$ pip install torch==1.4.0+cpu torchvision==0.5.0+cpu -f https://download.pytorch.org/whl/torch_stable.html
$ pip install opencv-python==3.4.4.19 opencv-contrib-python==3.4.4.19
$ pip install jupyter matplotlib 
$ pip install h5py
```
如果pytorch安装缓慢建议改为国内源安装：
``` cmd
$ pip install torch==1.4.0+cpu torchvision==0.5.0+cpu -i  https://pypi.mirrors.ustc.edu.cn/simple
```
