#翻译

为了防止多位翻译者工作冲突，翻译之前请先到下面的维基页面领受工作任务。

- [翻译任务领受单](https://github.com/gotgit/git-l10n-zh-cn/wiki/TaskList)

注意领受的工作任务尽量在12小时之内完成翻译并创建 Pull request。

#校验

## 本地测试 (Ubuntu 环境)

	1. 下载 git 最新版[源码](https://github.com/git/git)

		git clone git://github.com/git/git.git

	2. 下载 git 中文版 po 文件

		git clone git://github.com/gotgit/git-l10n-zh-cn.git
	
	3. 把 git-l10n-zh-cn/zh_cn.po 复制到 git/po 目录下，并改名为 zh_CN.po

		cp git-l10n-zh-cn/zh_cn.po git/po/

	4. 编译及安装 git,然后就可以检验中文翻译了。

## 提交问题

	发现错误或不合理的翻译内容后，在 github 上 fork 本项目，修改后并创建 pull request 。
