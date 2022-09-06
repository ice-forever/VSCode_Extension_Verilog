# 注意事项！

<b>out/vTbgenerator.py</b>：该文件是VS Code商店中生成TestBench文件的python代码文件。修改了以下内容：

- 删除了生成的复位信号

- 添加了将终端内容保存到文件的功能（命名格式：tb_<处理的文件名>.v）

<b>如果python3提示缺少模块charset，请安装所有缺少的库。</b>


# verilog-testbench-instance README

This extension "verilog-testbench-instance" can be used to enhance verilog programming capability. 

## Features

It includes two command, Testbench(generate testbench for verilog module in active editor) and Instance(generate instance for verilog module in active editor).

For example if there is active editor of verilog module, you press ctrl+ shift + p to select command:

![image](https://github.com/truecrab/VSCode_Extension_Verilog/raw/master/images/fig1.png)

It will generate the testbench in a new terminal.

![image](https://github.com/truecrab/VSCode_Extension_Verilog/raw/master/images/fig2.png)


## Requirements

It need **python3** environment.

## Extension Settings

This extension contributes the following settings:

* `Testbench`: generate testbench for verilog module in active editor
* `Instance`: generate instance for verilog module in active editor

## Known Issues

* `Install failed`: If you failed to install this extension, you may be update your vscode to version 1.23.

It is not known what the other issues are.

## Release Notes

The github address: https://github.com/truecrab/VSCode_Extension_Verilog

### 1.0.0

2018/05/07
The initial version.
It can generate testbench and instance for verilog module.

### 1.0.1

2018/05/07
Fixed README.md.

### 1.0.2

2018/05/07
Fixed README.md to display figure.

### 1.0.3

2018/05/07
Delete out in .gitignore for upload out folder.

### 1.0.5
2018/05/08
Modify the file open operation to fixed decoding problem in China.

-----------------------------------------------------------------------------------------------------------

## Other


**Enjoy!**
