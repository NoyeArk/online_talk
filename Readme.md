# 基于TCP协议的简易聊天室程序设计

## 设计要求

该项目是计算机网络的课程设计，最终成绩为优秀。

设计要求：使用**Java**编程语言，设计并实现一个基于TCP协议的简易聊天室程序。

程序包括**服务器端和多个客户端**，客户端能够连接到服务器并实现实时的聊天功能。

实现基本的用户登录、消息发送和接收功能。

## 功能实现

1. 群聊功能
2. 私聊功能
3. 服务器禁言、解除禁言功能
4. 服务器强制下线功能

## 程序概述

详见[计网课设：基于TCP协议的简历聊天室程序设计](https://zhouzimu.top/2024/06/22/%E8%AE%A1%E7%BD%91%E8%AF%BE%E8%AE%BE%EF%BC%9A%E5%9F%BA%E4%BA%8ETCP%E5%8D%8F%E8%AE%AE%E7%9A%84%E7%AE%80%E5%8E%86%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1/)

## 文件说明

```text
├─.idea        // idea的IDE配置文件
├─com
│  ├─Client    // 客户端实现
│  ├─DataBase  // 数据库操作
│  ├─GUI       // 登录界面实现
│  └─Server    // 服务器实现
├─img          // 图片资源
├─libs         // 依赖
├─secret       // AES加密算法
└─target       // 生成的目标文件
```
