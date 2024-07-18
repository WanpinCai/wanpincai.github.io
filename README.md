> 该主题根据 Hugo PaperMod 主题修改而来: https://github.com/adityatelange/hugo-PaperMod

## 1. git clone 拉取代码

① 用`git clone`的方式拉取代码至桌面，此时会在桌面生成 sulv-hugo-papermod 目录

② 进入到 sulv-hugo-papermod 目录，输入`git submodule update --init`，表示拉取 themes/hugo-PaperMod/下的子模块，里面放的是官方主题

## 2. 启动界面

③ 把目录定位到 sulv-hugo-papermod 下，在终端输入`hugo server -D`，在浏览器输入：localhost:1313 即可看到现成的博客模板。

## 3. 修改信息

模板内部有许多个人信息需要自己配置，请耐心修改完，可以参考博主的建站教程：[https://www.sulvblog.cn/posts/blog/](https://www.sulvblog.cn/posts/blog/)

## 4. shortcodes 使用方法

`bilibili: {{< bilibili BV1Fh411e7ZH(填 bvid) >}}`

`youtube: {{< youtube w7Ft2ymGmfc >}}`

`ppt: {{< ppt src="网址" >}}`

`douban: {{< douban src="网址" >}}`
