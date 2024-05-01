# Antivirus identification
-----------------------------------------------------------------
5-1假期后发布
============


杀毒软件进程识别，脚本内置了相关杀毒软件进程，直接执行即可得知存在什么杀毒软件，不需要自己执行命令。

Anti-virus software process identification, the script built-in anti-virus software process, directly execute to know what anti-virus software exists, do not need to execute their own commands.


因为部分机器不带Python环境，所以编译成了一个exe程序，直接执行exe程序后，会在当前路径下生成一个scan_ok.txt文件，文件内容就是当前机器所存在的杀毒软件

Because some machines do not have a Python environment, it is compiled into an exe program, and after directly executing the exe program, a scan_ok.txt file is generated in the current path, and the file is the anti-virus software existing in the current machine




1.tasklist命令版py脚本测试结果
![tasklist_py](https://upload.cc/i1/2024/05/01/oLFntZ.png)
tasklist命令版exe程序测试结果
![tasklist_exe](https://upload.cc/i1/2024/05/01/6Bm7Qr.png)
-----------------------------------------------------------------
为了防止意外，所以增加了一个wmic的，防止执行tasklist命令无回显或其他问题
-----------------------------------------------------------------
2.wmic process list brief命令版py脚本测试结果
![wmic process list brief](https://upload.cc/i1/2024/05/01/KXt4ld.png)
wmic process list brief命令版exe程序测试结果
![wmic process_exe](https://upload.cc/i1/2024/05/01/Oknr4m.png)
-----------------------------------------------------------------

打包成exe后的程序仅供6.99mb大小。
[img](https://upload.cc/i1/2024/05/01/JICiQW.png)
-----------------------------------------------------------------
1.tasklist命令exe程序实际机器测试结果
![tasklist_py](https://upload.cc/i1/2024/05/01/JWfuRM.jpg)
2.wmic process list brief命令exe程序实际机器测试结果
![wmic process_exe](https://upload.cc/i1/2024/05/01/gyNwIi.jpg)
-----------------------------------------------------------------
