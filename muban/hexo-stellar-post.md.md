---
# Hexo 内置核心字段
title: "<% tp.file.title %>" # 标题，自动使用文件名
date: <% tp.date.now("YYYY-MM-DD HH:mm:ss") %> # 自动填入当前时间
updated: <% tp.file.last_modified_date("YYYY-MM-DD HH:mm:ss") %> # 最后更新时间
layout: post # 布局，通常为 post
tags: [""]
categories: [""]
sticky: # 文章置顶，数字越大越靠前
comments: true # 是否开启评论，默认 true
permalink: # 自定义文章永久链接
excerpt: # 纯文本摘要，若不填默认截取文章前部分
published: true # 是否发布到线上
description: # SEO 描述，通常会自动生成
cover: # 文章封面图

# Stellar 主题特有字段
author: # 文章作者，1.23.0+ 可用
banner: # 页面顶部横幅背景图（可填链接或本地路径）
banner_info: # 横幅信息配置
poster: # 文章封面，支持更复杂配置
  topic: # 封面主题
  headline: # 封面标题
  caption: # 封面字幕
  color: # 封面颜色
topic: # 所属话题/专栏，1.25.0+ 可用
sidebar: # 侧边栏配置，1.0.0~1.26.8
leftbar: # 左侧边栏配置，1.27.0+ 可用
rightbar: # 右侧边栏配置，1.27.0+ 可用
wiki: # 所属 wiki，填写项目 ID
menu_id: # 高亮菜单项的 id
comment_title: # 评论区自定义标题
indent: false # 段落是否首行缩进
h1: # 页内一级标题，若不填则使用 title
type: # 页面类型，1.26.0+ 可用
references: # 参考资料
breadcrumb: true # 是否显示面包屑导航
indexing: true # 是否允许搜索引擎收录

# 第三方插件支持（按需开启）
mathjax: false # 启用 MathJax 渲染数学公式
katex: false # 启用 KaTeX 渲染数学公式（一般二选一）
mermaid: false # 启用 Mermaid 图表
---
