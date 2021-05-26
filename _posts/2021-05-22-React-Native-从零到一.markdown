---
layout: post
title: React Native 从零到一
date: 2021-05-22 14:15:40
description: 从零到一学会使用React Native进行跨平台应用开发 # Add post description (optional)
img: react-native.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [web, ios, android, Hybrid]
---

本教程适用于任何想要使用React Native进行跨平台应用开发的开发者阅读。

其实，[React Native官方中文教程](https://reactnative.cn)已经讲述的非常详细，本教程中也会大量的引用官方文档的内容。但是，由于官方教程存在一些没跟上时代步伐的坑，本教程主要是在官方教程的基础上针对目前会出现的问题进行填补。

教程主要包含以下几部分：
* React Native是什么
* 开发环境搭建
* 第一个React Native应用
* 使用模拟器、真机进行应用调试

# React Native是什么
简单来说，React Native是一个使用React开发移动端应用的开发框架。React Native利用js调用iOS和Android端的原生组件，开发出的APP，具有接近原生应用的交互体验。

# 开发环境搭建
React Native官方中文教程中有保姆级的[环境搭建教程](https://www.react-native.cn/docs/environment-setup)，包含macOS、Windows、Linux三个平台，大家跟着一步一步做就可以搭建成功。

## 注意事项
* 官方教程中背景标黄的注意事项**非常重要！**往往搭建不成功的案例都是忽略了注意事项中的内容。
* 能科学上网的同学，在搭建过程中可以减少很多不必要的坑。