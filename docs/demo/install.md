## 安装Labvision

labvision已整合进pypi源, 使用pip安装即可:

```
$ pip install labvision -i https://pypi.org/simple
```

安装后可在终端简单测试:
```
$ python
>>> import labvision
>>> print labvision.io.gpu.cuda_available()
True
```

<font color='grey'>如果出现问题,  说明作者又写了一堆bug , 大概率不是你的问题. </font>
<font color='grey'>请在[repo](https://github.com/klrc/labvision/issues) 提交issue, 贡献一份力量!</font>



现在, Labvision已经可以投入使用了.