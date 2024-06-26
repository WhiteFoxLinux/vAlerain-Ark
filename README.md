# vAlerain-Ark(A C++based Ark aimed at solving security personnel issues)


English | [简体中文](https://github.com/WhiteFoxLinux/vAlerain-Ark/blob/main/README-zh.MD) | [繁體中文](https://github.com/WhiteFoxLinux/vAlerain-Ark/blob/main/README-tw.MD)

_Ark是Anti-Rootkit（对抗恶意程序）的简写, vAlerainArk目标成为逆向工程师、编程人员的工具，同时也能为那些希望清理恶意软件的用户服务。 以后也将会支持更多功能和命令。_

![image](https://img.shields.io/badge/Windows-tool-blue)
![image](https://img.shields.io/badge/Windows-vAlerian-gree)
![image](https://img.shields.io/badge/Windows-Ark-blue)
![image](https://img.shields.io/badge/Windows-Ring3-gree)
![image](https://img.shields.io/badge/Windows-Ring0-gree)
![image](https://img.shields.io/badge/Windows-API-gree)




# F&Q
## What can I use your ark for?
My Ark currently has relatively few functions that can be implemented, only managing processes and services, as well as hook, dump, and other functions that will be implemented soon.
## How do you consider the future when your functionality is so advanced?
Although I also know that our features are limited, they will gradually update, such as innovating by removing PPLs and preventing drivers from turning on and off, and my drivers are written too junk and ready for refactoring.
## What was your original intention for developing Ark?
At first, the author liked to use the Velvet Sword, but later it was taken down. As the author was studying the Windows kernel and preparing to write an ark to understand the kernel and pagination, this project was created.

## 1.0.0.3
* Using snapshots to enumerate process lists
* Use process ID to end the process
* Use process PID to end the process tree
* Can recognize process handles

## 1.0.0.2
* Optimized startup animation
* Support ending, freezing, and ending process trees, viewing process paths, and copying process information
* Support replication of service name and registry information
* Support reading, viewing, and modifying Windows file associations
* Support for enumeration and operation of Windows service driver registry
* Windows message hook, mouse and keyboard hook testing and callback
* Support checking windowsPE structure file analysis
* Support Windows local proxy changes

## 1.0.0.1
* Optimized startup animation
* Support for ending, freezing, and ending process trees, viewing process paths, and copying process information for processes
* Support for reading, viewing, and modifying Windows file associations
* Enumeration and operation support for the registry of Windows service drivers
* Hook testing and callback for Windows message hooks, mouse and keyboard
* Support checking windowsPE structure file analysis
* Support for Windows local proxy changes

## v1.0.0.0

* Support for ending, freezing, and ending process trees, viewing process paths, and copying process information for processes
* Support for reading, viewing, and modifying Windows file associations
* Enumeration and operation support for the registry of Windows service drivers
* Hook testing and callback for Windows message hooks, mouse and keyboard
* Support checking windowsPE structure file analysis
* Support for Windows local proxy changes

# The source code usage standard is based on C++17
We strongly recommend using CLion compilation, and you can also use Microsoft's VS but never use dev cpp.

# **Special thanks**
* CLion's technical support
* _vAlerain_ Develop;Code from Mr. _vAlerain_;
* Long term evaluation and repair of _SNbing54_
  
