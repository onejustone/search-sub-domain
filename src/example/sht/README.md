# 赛会通个人活动信息爬取

## 目标

[赛会通](http://www.saihuitong.com/)

## 获取

## 背景故事

编程赋予了程序员一种上帝技能，让我们不在止步于意淫和幻想的阶段，而是可以将那些幻想中的东西在现实世界中得以显现，程序员的世界或许总是那么天马星空。

首先搜集赛汇通所有的子级域名，比如`http://chuxin.360jlb.cn/`, `luozi.http://chuxin.360jlb.cn/` 这种，当然考虑到信息搜集的难度，只考虑`2-6`个字符域名长度的情况。
然后根据目标`id`，定时自动爬取所有赛汇通子级域名下的最新参与活动信息，如果目标有新的活动动态，发送邮件自动提醒。

## reference

* Kali Linux
*