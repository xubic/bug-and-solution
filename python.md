问题描述：
Error processing line 1 of C:\guangting\anaconda\lib\site-packages\distutils-precedence.pth:
  Traceback (most recent call last):
    File "C:\guangting\anaconda\lib\site.py", line 169, in addpackage
      exec(line)
    File "<string>", line 1, in <module>
  ModuleNotFoundError: No module named '_distutils_hack'

解决：
找到C:\guangting\anaconda\lib\site-packages\distutils-precedence.pth
用记事本打开distutils-precedence.pth
在第一行的最开头的“import os;”后面加上一个enter换行
