## 公主连结自动化任务 

git: https://github.com/smartgrass/AutoPcr

b站: https://www.bilibili.com/video/BV14a411q7uA

不会python的先看这里: https://github.com/smartgrass/AutoPcr/blob/main/png/python%E5%AE%89%E8%A3%85%E8%AF%B4%E6%98%8E.md

<img src="https://github.com/smartgrass/AutoPcr/blob/main/png/Top.png" width= "500"/>

# 更新5.5 可挂后台版本

跳过启动时生日

使用win32gui代替鼠标点击, 运行时可挂后台,但不能最小化

# 更新5.0绿龙自动刀版本(仅限Windows) 

功能渐渐花里胡哨了起来...

<img src="https://github.com/smartgrass/AutoPcr/blob/main/png/GUIWindow.png" width= "500"/>

运行配置见'运行说明'文件夹

步骤: 

1.安装py

2.安装py第三方库: 运行 SetupPip.cmd (管理员

3.设置管理员权限 : (把python.exe的启动改为管理员模式)

4.配好雷电模拟器路径, 配好模拟器快捷按钮

5.运行

# 提示:

1.本源码供学习用，禁止用于商业相关

2.使用时不能有中文路径

3.Esc可退出程序

### 运行失败原因
1.没有安装python

2.没安装第三方库 解决: 管理员模式运行SetupPip.cmd

3.文件夹有中文路径

4.GUI版模拟器启动不了?  解决: 模拟器路径改完 需要点击保存路径

5.没有使用管理员模式运行 解决:将python.exe设置为管理员方式启动:

-属性->兼容性->更改所有用户设置->√管理员身份运行

-建议模拟器启动也设为管理员模拟式启动


# 运行需求:
Windows
python环境, 没用过python的还是不推荐去用了


## 1.py核心库:

 aircv 做图像识别;
 
 pyautogui库做按钮键盘事件;
 
 PIL库做屏幕截图;
 
 keyboard 做键盘事件检测
 
管理员模式运行 "SetupPip.cmd" 安装

