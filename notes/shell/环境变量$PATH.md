#### $PATH

- PATH的值是以冒号分割的目录列表，我们可以查看PATH的内容
- 如果PATH中没有包含该目录，自己手动添加也不麻烦，把下面这行 ``` export PATH=~/bin:"$PATH" ``` 加入.bashrc文件中即可
- 示例代码

``` shell
$ echo $PATH  
/home/me/bin:/usr/local/sbin
```