# To apply Tsinghua Mirrors on "pip install"
## Once:
```
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple some-package
```
## Globally:
```
python -m pip install --upgrade pip
pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
```
