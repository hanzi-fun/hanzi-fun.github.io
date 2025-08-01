---
title: Change Log
author: TieJun
date: 2022-02-04
category: Log
layout: post
---

感谢您的选择！

## Version 1.0.7
- Updated 给【千字文】和【三字经】每个字添加点击，方便查看相关字的显示
- Added 【学习】：添加【考核】功能（听写相关需要打开语音引擎）

## Version 1.0.6
- Updated 尝试不使用分包：因为部分用户根本不知道如何使用～
- Changed 汉字详情页: 优化记录已经学习过的汉字
- Updated 更新Google Play Core : 移除`api("com.google.android.play:core:1.10.3")`
添加
```kotlin
    api("com.google.android.play:review-ktx:2.0.1") //点评
    api("com.google.android.play:app-update-ktx:2.1.0") //更新
    api("com.google.android.play:feature-delivery-ktx:2.1.0") // 分包
    api("com.google.android.play:asset-delivery-ktx:2.2.2") //资源分包
```
- Add 增加离线翻译功能(基于google)，增加更多翻译模型的显示
- Add 增加APP点评入口

## Version 1.0.5（未发布）
- Updated 更新基础类库,优化App主题：新增对比度中、对比度高的主题
- Updated 部分界面UI调整

## Version 1.0.4
- Fixed 低版本手机本地数据库初次加载问题：问题严重
- Added 添加学习日历：每日学习的汉字和词语
- Added 分屏处理：对于Table设备进行分屏处理
- Updated 更新基础类库

## Version 1.0.3
- Fixed 翻译优化：当翻译模型没有下载的时候，隐藏翻译功能
- Changed 优化搜索：优化部分点击事件，优化只搜索具体类型的内容
- Fixed 内容修复:修复部分内容拼音错误
- Changed 优化翻译：添加翻译模块后，词语中的单个字的解释可以进行翻译
- Added 声音朗读：拼音、千字文、百家姓、三字经

## Version 1.0.2
- Fixed 汉字结构：修复release导致的崩溃问题

## Version 1.0.1
- Changed 词语详情页：把其他信息中的近义词和反义词单独取出展示，方便查看对应详情
- Removed 汉字详情页：底部的其他信息移除 
- Fixed 汉字列表：修复列表详情自动滚动到上次位置存在异常
- Added 优化搜索：新增特定词语结构查询：ABAC（一五一十）/ABBC（自欺欺人）/ABCC（一表堂堂）等

## Version 1.0.0
- Changed 优化icon

## Version 0.0.6
- Added 汉字列表界面记录上次的位置，下次进入自动滚动到对应的位置
- Added 汉字详情和词语详情新增滚过的字的显示标题
- Fix 搜索当从有结果的界面到搜索无结果的界面时，存在的展示和崩溃问题

## Version 0.0.5
- Fixed  笔画笔顺的动画问题导致的微弱卡顿现象
- Fixed  汉字详情介绍展示问题
- Fixed  搜索功能的崩溃bug

## Version 0.0.4
- Added 优化搜索功能：新增支持拼音/汉字结构/笔画数
- Added 无障碍相关提醒

## Version 0.0.3
- Added 新增翻译功能：中文翻译-英文
- Added 新增文字转语音功能：使用的系统功能，需要系统支持中文
- Added 新增笔画笔顺功能：下载功能后，支持汉字的笔画笔顺书写

## Version 0.0.2
- Added 汉字详情：拼音+笔画+词语+解释
- Added 收藏功能
- Added 笔记功能 [暂时隐藏]
- Added 搜索功能：汉字（部首/汉字/词语）

## Version 0.0.1
- Added 拼音基础
- Added 偏旁部首
- Added 汉字结构
- Added 汉字分级学习
- Added 三字经
- Added 千字文