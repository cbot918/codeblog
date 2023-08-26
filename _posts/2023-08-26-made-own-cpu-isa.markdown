---
layout: post
title:  (整理) Made Own Instruction And CPU Emulator 
date:   2023-08-26 16:45:00 +0800
image:  02.jpg
tags:   Resources
---

此系列教學是已退休的資深軟體工程師的教學影片, 從自己設計指令集開始, 設計組譯器(處理組合語言的), 到設計CPU模擬器. 這方面領域知識博大精深, 自己也只能略懂5%並把程式執行起來做研究觀察, 還無法覺得自己了解了, 只好繼續努力, 以下做此系列分享.

## 解決問題
有個具體而微的學習脈絡了解指令集/CPU/組合語言

## 小提醒
具備一點作業系統及編譯器的基礎知識會比較好理解

## 環境(如果OS不支援, 可以使用VM)
1. Python

## 教學三部曲
### 1. [Design Your Own CPU Instruction Set](https://www.youtube.com/watch?v=wjHlvQfo5uI&t=9s)

在這部影片裡, Gary手把手設計指令集的步驟, 用很簡單且可操作的方式解釋並呈現出來, 至此我們已經有自己設計的指令集, 會需要一個組譯器

### 2. [How Does A CPU Work? - Assembly Language](https://www.youtube.com/watch?v=af0Vy488ouI&t=10s)

這部影片是組合語言的教學

### 3. [Write Your Own Emulator for Your Own CPU](https://www.youtube.com/watch?v=R6KBHeJ-RDs)

這部影片解釋組譯器設計, CPU模擬器設計, 沒有完整的手把手寫code(畢竟是介紹影片)

## Repos

[Gary本人的Repo](https://github.com/garyexplains/examples)

[我整理過可以直接跑得Repo](https://github.com/cbot918/cpu-py)

## 補充 
一個超棒的1.5H的NASM教學：[x86 NASM Assembly Crash Course](https://www.youtube.com/watch?v=DNPjBvZxE3E&t=21s)
## 後記
轉職工程師之前, 自己就有個目標是想要精通電腦, 直到當上工程師之後, 發現幾乎是天方夜譚. 但以前教授教過逐個擊破的方法(我沒畢業的資工仔), 所以我在閒暇時間, 自學作業系統/處理器. 歸功於Gary的知識統整以及Python的簡潔, 可以用相對簡單的方式, 理解吸收複雜深奧的CPU/組合語言/模擬器等等知識, 雖然都還只是基礎, 但是感謝此教材可以讓我抓著重點學習, 還需要更多的努力及研究, 幫自己加油！