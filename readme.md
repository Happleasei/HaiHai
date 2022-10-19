## 
### 介绍
```
个人对话机器人 -- 嗨嗨
```
```
安装方式: 
pip install haichatbot
```
#### 主目录
```
/
├── 
└── README.md            # 介绍文档
```
> 
#### 如何上传自己的包
```
python setup.py check
python setup.py register sdist upload -r http://pypi.org
python setup.py bdist_egg
twine upload dist/*
```