date: 2020/4/14 5:59 下午 

1. 准备环境
```
pip install numpy==1.14.0
pip install torch==1.0.0
pip install jupyter-notebook
-i https://pypi.tuna.tsinghua.edu.cn/simple
```

2. 测试

```
python main.py --status test
相关配置文件在configure.py

pid 17298
```
测试结果在：
http://haomeiya002:8892/notebooks/note.ipynb

SanWen：
Test: time: 802.49s; f1: 0.6714; auc: 0.6050

FinRE：
Test: time: 1522.51s; f1: 0.5129; auc: 0.3970

3. 训练

上周在haomeiya003 GPU机器已经训练完毕，将模型文件拷贝保存。
