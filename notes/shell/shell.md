#### 什么是shell

- Shell的独特之处在于它既是系统强大的命令行接口，又是脚本语言解释器。我们会看到在命令行能完成的大部分事情也可以在脚本中搞定，反之亦然。

#### 如何创建并执行脚本

- 编写脚本
    - #！是一种shebang(sharp-bang)的特殊构件，用于告诉内核该使用哪个解释器来执行接下来的脚本。所有的shell脚本都应该将其作为第一行。
    - 为了减少输入，在命令行上输入选项时，短选项更为可取，但是在编写脚本时，长选项可以增强可读性。
    - 可以利用反斜线（\）进行续行，利用tab缩进。脚本和命令行的一个区别是脚本可以利用制表符来缩进，而命令行不行，因为按下Tab会激活自动补齐功能。
- 将脚本设置为可执行
    - 系统不会为任何文件视为可执行程序，我们需要手动设置脚本的可执行权限。
- 把脚本放在Shell能够找到的地方。
    - 如果我们编写了一个允许系统所有用户都可以使用的脚本，那么这类脚本的传统存放位置是/usr/local/bin.超级用户使用的脚本通常放在/usr/local/sbin 