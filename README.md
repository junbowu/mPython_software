
# mPython软件
The mPython software is a branch of the [Mu](https://github.com/mu-editor/mu) . It adds support of the mPython board (or others ESP32 core hardware).

mPython软件是开源软件 [Mu](https://github.com/mu-editor/mu) 的一个分支，它增加了对掌控板（或同类ESP32核心硬件）的支持。

mPython掌控板是一块MicroPython微控制器板，它集成ESP32高性能双核芯片，使用当下最流行的Python编程语言，以便您轻松地将代码从桌面传输到微控制器或嵌入式系统。

![](https://github.com/labplus-cn/mPython/blob/master/docs/images/掌控-立1.png)  

GitHub: https://github.com/labplus-cn/mPython    <br/>
mPython掌控板在线文档: https://mPython.readthedocs.io

## 更新日志
### 0.2.3
* 修改“运行”按钮为实时运行
### 0.2.4
* 增加恢复固件功能
* 修复部分电脑不能右键运行和实时运行的bug
* 交互时允许粘贴中文
* 右键允许运行中文文件名
### 0.2.5
* 代码运行出错时，弹出调试信息
* 联网自动更新：mpython.py库、和软件内置固件
* 接入掌控板时，如板载固件不一致，提示是否需要更新固件
* 刷入python文件后，提示运行

## 软件下载地址
目前有三个下载地址（for Windows 64位、Windows 32位、MacOS）：

http://static.steamaker.cn/files/mPython2_0.2.5_win64.exe

http://static.steamaker.cn/files/mPython2_0.2.5_win32.exe

http://static.steamaker.cn/files/mPython2_0.2.5_macos.zip

## 软件使用教程
软件使用教程请参考[mpython文档](https://mpython.readthedocs.io/zh/latest/board/software.html)

## 开发环境配置
```
git clone https://github.com/labplus-cn/mPython_software.git
pip3 install -r requirements.txt
```
如果提示pip版本过低，可以运行一下命令更新pip
```
python -m pip install --upgrade pip
```
## 如何参与开源项目
* 完善mpython文档
* 测试软件bug
* 撰写mpython案例
* translate mpython to your native language

建议fork到自己的项目再提交
=======
=======

