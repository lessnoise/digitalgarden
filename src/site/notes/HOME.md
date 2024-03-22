---
{"dg-home":true,"dg-publish":true,"permalink":"/HOME/","tags":["gardenEntry"],"dgPassFrontmatter":true}
---


> [!quote]  
>  👏  Hi ，欢迎来到我的数字花园，一个基于 Obsidian 的双链个人知识博客

## 🗳️ 数字花园导航

- **[[🔗 双链博客说明书\|🔗 双链博客说明书]]**

## 🍀 探索花园小径

- **🧀 [[个人知识管理\|个人知识管理]]**
- **📰 [[优质长文分享\|优质长文分享]]**


> [!example]+ 最新内容 
> 
> - ```dataview
table without id
file.link as Note,
file.folder as Folder,
file.mtime as "Last Modified"
FROM -"Dailies"
where file.mtime > (date(now) - dur(12 hours))
sort file.mtime desc

👉 [[About Me\|About Me]]
