# vim 使用tip

### 编写python程序

1. 自动插入头信息：
    - `#!/usr/bin/env python`
    - `# coding=utf-8`
- 输入`.`或按`TAB`键会触发代码补全功能
- `:w`保存代码之后会自动检查代码错误与规范
- 按`F6`可以按`pep8`格式对代码格式优化
- 按`F5`可以一键执行代码


### 多窗口操作

1. 使用`:sp + 文件名`可以水平分割窗口
- 使用`:vs + 文件名`可以垂直分割窗口
- 使用`Ctrl + w`可以快速在窗口间切换

### 编写markdown文件

1. 编写markdown文件(`*.md`)的时候，在normal模式下按 `md` 即可在当前目录下生成相应的`html`文件
- 生成之后还是在normal模式按`fi`可以使用firefox打开相应的`html`文件预览
- 当然也可以使用万能的`F5`键来一键转换并打开预览
- 如果打开过程中屏幕出现一些混乱信息，可以按`Ctrl + l`来恢复

### 快速注释

- 按` \ ` 可以根据文件类型自动注释
- 

### NoteFAN添加
- 工作目录下生成tags: ctags -R *
- ctrl + ]: 跳转至函数或变量定义
- ctrl + t: 跳转返回
- Fn + F3(mac): 目录树打开/关闭（tablist-left）
- Fn + F9(mac): 类及结构体显示窗口（right）
- Fn + F6(mac): 格式化代码
- gg: 文档顶部
- G: 文档底部
- M: 文档中部
- ctrl + w: 窗口切换
- w/W: 下一个单词
- b/B: 前一个单词
- shift + $: 行尾
- shift + (: 上一行行首
- shift + ): 下一行行首

