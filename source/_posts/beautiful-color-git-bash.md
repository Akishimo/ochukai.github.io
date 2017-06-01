title: 给 Git Bash 设置好看的配色~ 😜
tags:
  - git bash
  - terminal
  - 配色
date: 2017-06-01 06:06:06
---

window 上面的命令行一直都非常丑陋 (看我用词多么强烈)~

今天上午终于因为看 Git Bash 配色而双眼变得模糊了, 于是上网搜了一下有没有结局方案, 然后就发现了这个 [github/mintty-colors-solarized](https://github.com/mavnn/mintty-colors-solarized), 但这个项目是好几年前的了, 我还是怀着试试看的态度尝试了一下.

我发现了, 干程序员别的可能不行, 但是尝试的能力还是有的, 经常为了找一个新的框架, 或者要写一个组件而去把所有相关的项目全看一边, 然后才发现不行~

但是今天老天并没有调戏我, 先说一下修改的过程吧~ 在 Git Bash 里面输入,

```
cd ~
vi .minttyrc
```

开始编辑它的配置文件, 不妨输入这些东西, 这些配色就是我从上面的项目里面找来的~

```shell
...
Font=Consolas

# 后面是颜色的配置
ForegroundColour=131,148,150
BackgroundColour=0,43,54
CursorColour=220,50,47

Black=7,54,66
BoldBlack=0,43,54
Red=220,50,47
BoldRed=203,75,22
Green=133,153,0
BoldGreen=88,110,117
Yellow=181,137,0
BoldYellow=101,123,131
Blue=38,139,210
BoldBlue=131,148,150
Magenta=211,54,130
BoldMagenta=108,113,196
Cyan=42,161,152
BoldCyan=147,161,161
White=238,232,213
BoldWhite=253,246,227
```

保存之后, 重启一下, 效果就像下面这样了~

![非选中状态](/images/terminal.png)

![选中状态](/images/terminal-selected.png)
