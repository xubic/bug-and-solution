问题描述：
Error processing line 1 of C:\guangting\anaconda\lib\site-packages\distutils-precedence.pth:
  Traceback (most recent call last):
    File "C:\guangting\anaconda\lib\site.py", line 169, in addpackage
      exec(line)
    File "<string>", line 1, in <module>
  ModuleNotFoundError: No module named '_distutils_hack'
![image](https://github.com/xubic/bug-and-solution/assets/61317271/c9fc1541-f9a4-4d90-9a00-9720adf79035)



解决：
找到C:\guangting\anaconda\lib\site-packages\distutils-precedence.pth
用记事本打开distutils-precedence.pth
![image](https://github.com/xubic/bug-and-solution/assets/61317271/fda32dbe-bf22-49cc-8ea4-49680dcd3248)

在第一行的最开头的“import os;”后面加上一个enter换行
![image](https://github.com/xubic/bug-and-solution/assets/61317271/29c94a73-e2e6-4935-9bad-384766d2ebc8)
