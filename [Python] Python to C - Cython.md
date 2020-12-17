# Cython

>[參考連結1](https://kknews.cc/zh-tw/code/gj9rkjy.html)

>[參考連結2](https://kknews.cc/zh-tw/code/gj9rkjy.html)

1. 修改變數與函數名稱 

`cpdef int test(int x)`

`cdef int a`

2. 建立Setup.py

`from distutils.core import setup 
from Cython.Build import cythonize 
setup(ext_modules = cythonize("hello.py"))`

3. 設定環境變數(VS2010 Compiler): `SET VS90COMNTOOLS=%VS100COMNTOOLS%`

4. 執行 `python setup.py build_ext --inplace`

4. 在檔案中引用 
   `import py2c
    py2c.test(6)`

