# xdg-desktop-portal

## 项目名称

xdg-desktop-portal 支持 treeland 的壁纸设置

## 项目描述

XDG Desktop Portal 是 XDG 定下的一套应用程序与桌面环境交互的接口。

XDG Desktop Portal 在架构上分为前端和后端，前端是应用程序访问的标准接口，后端是桌面环境提供的接口实现。

1. 在 xdg-desktop-portal-dde 中实现对 TreeLand 合成器的壁纸接口调用

## 项目导师

张丁元 `<zhangdingyuan@uniontech.com>`

## 赛题分类
未归类运行时支撑

## 难度

低

## 参考文档

1. https://flatpak.github.io/xdg-desktop-portal/docs/
2. https://github.com/linuxdeepin/xdg-desktop-portal-dde

## 预期目标

应用程序可以通过 xdg-desktop-portal 接口设置桌面壁纸

## 从题目中能学到什么

1. wayland 协议客户端部分的开发
2. xdg-desktop-portal 的架构及工作原理

## 涉及领域

1. Wayland
2. XDG spec
