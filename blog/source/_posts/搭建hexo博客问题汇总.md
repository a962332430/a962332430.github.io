---
title: 搭建hexo博客问题汇总
date: 2021-07-12 20:39:12
tags:
---

# hexo指令
```
# 写文章
hexo new hello
# 本地启动博客
hexo s
# 部署至github.io
hexo d
```

#3 搭建参考文档
https://segmentfault.com/a/1190000017986794
https://www.cnblogs.com/sha-ka/p/13250051.html

#3 当从不同电脑迁移hexo时，若出现无法启动server时，如下指令可以帮忙
$ npm install hexo --no-optional
if it doesn't work
try
$ npm uninstall hexo-cli -g
$ npm install hexo-cli -g
