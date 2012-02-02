## 翻译结束

- **翻译已告完成。** 已提交至官方邮件列表： http://marc.info/?l=git&m=132815949315059 （UTF-8字符集）
- 获取最新翻译及代码补丁访问: https://github.com/gotgit/git-po-zh_CN/commits/maint-zh-cn
- 后续维护方式Git官方正在讨论中： http://marc.info/?l=git&m=132815877514930
- 感谢 @riku, @zhuangya, @liancheng 的贡献

        $ msgfmt --statistics zh_CN.po 
        711 条已翻译消息.

翻译过程中使用维基协同，参见: [翻译任务领受单](https://github.com/gotgit/git-l10n-zh-cn/wiki/TaskList)

## 本地化方法

文件 `zh_CN.po` 已提交官方。在官方版本库接纳前，可用下面方法获取中文本地化文件及安装部署：

1. 获取中文本地化文件：

        $ curl -L https://github.com/gotgit/git-po-zh_CN/raw/maint-zh-cn/po/zh_CN.po > zh_CN.po

2. 将 `zh_CN.po` 文件复制到Git源码的 `po` 目录中。

        $ cp zh_CN.po path/to/git/po/

3. 编译及安装 git，然后就可以让Git说中文了。

        $ cd path/to/git/
        $ make all && sudo make install
