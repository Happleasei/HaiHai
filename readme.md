## 
### ����
```
���˶Ի������� -- ����
```
```
��װ��ʽ: 
pip install haichatbot
```
#### ��Ŀ¼
```
/
������ 
������ README.md            # �����ĵ�
```
> 
#### ����ϴ��Լ��İ�
```
python setup.py check
python setup.py register sdist upload -r http://pypi.org
python setup.py bdist_egg
twine upload dist/*
```