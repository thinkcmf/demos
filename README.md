# ThinkCMF演示
本仓库提供 ThinkCMF官方的一些演示应用、插件、模板和api，方便开发者学习 thinkcmf.

## 仓库镜像
1. https://github.com/thinkcmf/demos 主要仓库
2. https://gitee.com/thinkcmf/demos 中国镜像


## 安装portal应用
0. 先下载本仓库从[github](https://github.com/thinkcmf/demos/archive/master.zip)或[码云](https://gitee.com/thinkcmf/demos/repository/archive/master.zip)
1. 复制`app/portal`到5.1`app`目录
2. 执行数据库文件`app/portal/data/portal.sql`安装门户应用数据库，注意替换表前缀
3. 复制`public/themes/simpleboot3`到5.1`public/themes/`目录，到后台`设置->模板管理`安装并启用`simpleboot3`
4. 复制`public/themes/admin_simpleboot3`到5.1`public/themes/`目录
5. 到后台菜单管理导入新菜单

## 模板插件安装
复制它们到相应目录，再到ThinkCMF后台安装启用即可
