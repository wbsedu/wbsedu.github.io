# vscode+annconda python开发环境
## 1. conda
### 1.1 conda列出当前环境
    conda env list

### 1.2 创建虚拟环境
    conda create -n my_env python=3.7.6

### 1.3 进入环境
    source activate my_env

### 1.4 退出环境
    source deactivate

### 1.5 使用conda管理包
    进入环境后执行
    conda install numpy
    如果显示找不到包则

## 2. vscode python 插件setting
    "python Path": 
    "/home/free/anaconda3/envs/wbs/bin/python"

