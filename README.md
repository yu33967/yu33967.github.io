

#####  Github 静态网站

> 实现目标：实现URL访问的人个博客
>
> 实现路径：GITHUB

###### 1. 访问GITHUB网站 ，注册账号

![GITHUB_注册用户名与密码_1](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241708913.png)

![GITHUB_注册用户名与密码_2](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241708314.png)

![GITHUB_注册用户名与密码_3](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241708404.png)

###### 2. 创建仓库( 仓库名是:gitihub_name.github.io)

![GITHUB_静态网站所在的仓库_1](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241709528.png)

![GITHUB_静态网站所在的仓库_2](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241709968.png)

###### 3. 创建分支+设置静态网站（分支可mian 可创建新分支gh-pages）

![GITHUB_静态网站仓库分支-ph-pages_2](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241710826.png)

![GITHUB_设置PAGE_2](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241712613.png)

###### 4. 正常访问MD文件 (jekyll设置)。在仓库的根目标下创建'_config.yml'文件，有jekyll和markdown设置。

```yml
# 配置基本信息
title: '' 
# 你的博客标题
email: '' 
# 你的邮箱地址
description: '' 
# 描述你的博客
# 这里是博客的描述文本，可以写多行。
baseurl: "" # 如果你的仓库名不是用作博客的URL，请在这里设置相应的子路径
url: "https://yu33967.github.io" # 你的博客的完整URL
 
# 配置发布文章的目录
posts_dir: "."
 
# 配置分类和标签
default_category: 默认分类
category_map:
  python: Python
  jekyll: Jekyll
 
# 配置时间显示格式
timezone: "Asia/Shanghai"
 
# 配置Markdown解析器
markdown: kramdown
 
# 配置高级设置
kramdown:
  auto_ids: false
  footnote_nr: 1
  entity_output: as_char
  toc_levels: 1..6

```

###### 5. 测试链接

![测试网站-是否可以访问](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241717813.png)





