# Antivirus identification
杀毒软件进程识别，脚本内置了杀毒软件进程，直接执行即可得知存在什么杀毒软件，不需要执行tasklist命令。
Antivirus software process identification: The script has built-in antivirus software processes. You can directly execute the script to find out the existing antivirus software without running the tasklist command.


![](https://upload.cc/i1/2024/05/01/Jci7Hw.jpg)

机器没Python环境的话，已编译为exe程序，直接执行即可
If the machine does not have a Python environment, it has been compiled into an exe program and can be executed directly

执行打包好的exe程序后，会在当前目录下生成一个ok.txt文件，文件里记录了当前机器存在的杀毒软件进程
After executing the packaged exe program, an ok.txt file is generated in the current directory, which records the antivirus software process existing on the current machine
![](https://upload.cc/i1/2024/05/01/C0d8ez.jpg)
