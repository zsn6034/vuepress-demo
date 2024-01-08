---
lang: zh-CN
title: 标题啊啊啊
description: 描述啊啊啊
---

# Hello VuePress

你好啊

# 试一下各种 md 语法

## 1.表格

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

## 2.加粗、斜体、删除线

**aaaa**\
_aaaa_\
~~aaaa~~~

## 3.链接

<!-- 相对路径 -->

[首页](../README.md)  
[配置参考](../reference/config.md)  
[快速上手](./getting-started.md)

<!-- 绝对路径 -->

[指南](/zh/guide/README.md)  
[配置参考 > markdown.links](/zh/reference/config.md#links)

<!-- URL -->

[GitHub](https://github.com)

## 4.emoji

VuePress 2 已经发布 :tada: ！

## 5.目录

[[toc]]

## 6.代码块

```ts{1,6-8}
import { defaultTheme, defineUserConfig } from "vuepress";

export default defineUserConfig({
  title: "你好， VuePress",

  theme: defaultTheme({
    logo: "https://vuejs.org/images/logo.png",
  }),
});
```

## 7.使用 vue

一加一等于： {{ 1 + 1 }}

<span v-for="i in 3"> span: {{ i }} </span>

这是默认主题内置的 `<Badge />` 组件 <Badge text="演示" />
