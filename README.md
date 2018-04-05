## Overview

我的博客使用的 NeXT 主题，由于修改了部分样式，而且配置 `_config.xml` 的过程相当漫长，因此 fork 在这里保存一下，方便下次迁移。

## Quick Start

Hexo 文件夹下装这些依赖，开启本地搜索：

```shell
$ npm i -S hexo-generator-searchdb
```

在本主题目录下安装这些依赖，开启进度条、fancybox：

```shell
$ git clone https://github.com/theme-next/theme-next-reading-progress source/lib/reading_progress

$ git clone https://github.com/theme-next/theme-next-fancybox3 source/lib/fancybox
```

## Modification

对原 NeXT 主题的样式修改有：

- 在 `images` 里加入了自己的头像和网站 Icon
- 整站字号从 14px 增大至 16px
- 文章里的链接、引用块、行内代码样式修改
- 首页「阅读全文」链接样式修改