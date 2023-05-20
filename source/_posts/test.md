---
title: test
date: 2023-05-20 19:46:22
tags:
---


# 这是一级标题

> 护凉网的朋友们大家好~
> 这里是引用内容

在 _config.butterfly.yml 文件中将以下配置进行修改，可以实现首页打字机特效：

```yaml
subtitle:
  enable: false
  effect: true
  typed_option:
  source: false
  sub:
```

修改为：

```yaml
subtitle:
  enable: true
  effect: true
  typed_option:
  source: 3
  sub:
    - My First Blog
    - I LOVE FISHC
```

修改的代码将注释给移除了，建议在配置文件中可以保留注释，以防万一忘记配置含义。
此时，开启了打字机效果，且默认会先调用今日诗词，随机打印一句后，打印 sub 配置的内容

