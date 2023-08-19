#### read

- 内建命令read可以从标准输入读取一行。该命令可以读取键盘输入，如果使用了重定向，也可以读取文件的数据行。
- ``` read [-option] [variable...] ``` option是列出的一个或多个选项，variable是一个或多个选项，用于保存输入值。如果未指定变量，则输入值保存在shell变量REPLY中。
    - read可以将输入赋值给多个变量
    - 如果read接受到的值少于预期，则多出的变量为空值；如果数量多于预期值，则额外的输入全部保存在最后一个变量中；如果没有为read命令指定变量，则所有的输入全部保存在shell变量REPLY中。
- 我们使用echo命令（-n选项不输出结尾的换行符）来显示提示信息，然后使用read命令将输入赋给int变量。
- ![read1.jpeg](..%2F..%2F..%2Fstatic%2Fimages%2Fread1.jpeg)
- ![read2.jpeg](..%2F..%2F..%2Fstatic%2Fimages%2Fread2.jpeg)
- ![read3.jpeg](..%2F..%2F..%2Fstatic%2Fimages%2Fread3.jpeg)
- ![read4.jpeg](..%2F..%2F..%2Fstatic%2Fimages%2Fread4.jpeg)

#### IFS

- 输入参数的分隔符
    - 默认为空哥符、制表符、换行符
    - 可以临时更改
    - ![IFS1.jpeg](..%2F..%2F..%2Fstatic%2Fimages%2FIFS1.jpeg)
    - ![IFS2.jpeg](..%2F..%2F..%2Fstatic%2Fimages%2FIFS2.jpeg)
- 验证输入
- ![验证输入1.jpeg](..%2F..%2F..%2Fstatic%2Fimages%2F%E9%AA%8C%E8%AF%81%E8%BE%93%E5%85%A51.jpeg)
- ![验证输入2.jpeg](..%2F..%2F..%2Fstatic%2Fimages%2F%E9%AA%8C%E8%AF%81%E8%BE%93%E5%85%A52.jpeg)

#### 菜单

- ![菜单1.jpeg](..%2F..%2F..%2Fstatic%2Fimages%2F%E8%8F%9C%E5%8D%951.jpeg)
- ![菜单2.jpeg](..%2F..%2F..%2Fstatic%2Fimages%2F%E8%8F%9C%E5%8D%952.jpeg)
- ![菜单3.jpeg](..%2F..%2F..%2Fstatic%2Fimages%2F%E8%8F%9C%E5%8D%953.jpeg)
