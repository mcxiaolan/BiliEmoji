# BiliEmoji
 B站表情链接收集
 
如有部分表情遗漏，欢迎提交[issues](https://github.com/lrhtony/biliEmoji/issues)

本项目随缘更新

## 收集方法
通过爬取<https://api.bilibili.com/x/emote/package>进行收集

## 链接使用
图片格式化 ，具体可参考：<https://github.com/SocialSisterYi/bilibili-API-collect/blob/master/other/picture.md>

## 评论支持
目前已支持[Waline](https://waline.js.org)自定义表情，详细链接请查看`src`下各表情目录

链接：
```
https://cdn.jsdelivr.net/gh/lrhtony/BiliEmoji@latest/src/表情
```
或者使用Cloudflare
```
https://vup.pages.dev/src/表情
```
~~或者unpkg及其知乎镜像~~(速度不理想停止使用)
```
https://unpkg.com/bili_emoji@latest/src/表情
https://unpkg.zhimg.com/bili_emoji@latest/src/表情
```


## 注意
- 请根据实际使用情况自行更改数据形式，勿将本项目直接应用于生产环境
- 如原表情链接被新表情链接取代，则原链接的名称将改为 `[原表情名]-旧` 的形式

## 说明
Bilibili 表情的版权归原作者所有