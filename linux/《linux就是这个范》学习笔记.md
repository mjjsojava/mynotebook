---
title: 《linux就是这个范》学习笔记
tags: ["linux"]
notebook: linux
---

# 第一部分 基础篇

### 第1章 第一次亲密接触

##### 1.1 让Linux入驻我们的电脑
    
    
    浏览器：Firefox、Chrome、Opera  
    Office：WPS  
    聊天工具：忽略 也可以用WebQQ  
    发行版：RHEL  SUSE  Ubuntu
    

##### 1.2 不一样的图形操作
    
    
    X：linux图形界面协议  
    xorg: linux下实现X协议的服务器软件  
    WM：窗口管理器，KDE GNOME等包括各自的窗口管理器  
    startx 启动图形界面  
    DM：显示管理器，负责图形界面的用户登录问题 包括XDM KDM GDM等
    

![](https://raw.githubusercontent.com/mjjsojava/MarkdownPhotos/master/%E3%80%8ALinux%E5%B0%B1%E6%98%AF%E8%BF%99%E4%B8%AA%E8%8C%83%E3%80%8B/01_01.png)

##### 1.3 主流桌面环境
    
    
    GNOME KDE XFACE LXDE  
    不是单一软件，而是一套软件集合，比如WM DM 应用框架库等
    

##### 1.4 返璞归真的命令行  

    用户通过shell同系统打交道  
    命令行和图形界面切换：Ctrl><Alt><F1>~ <F6> 命令行 <Ctrl><Alt><F7> 图形界面  
    常用命令：  
    mkdir  ls  cd  pwd  cp mv rm cat more less head  tail echo  ps  kill  jobs  bg  fg  du  df  



