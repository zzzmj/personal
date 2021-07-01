## 个人配置

本仓库保存了一些私人的配置，便于查找与转移



### 1. mac快捷键



方案如下：

```
 约定：
        C为Ctrl键
        W为alt 键
        S为Shift键
    移动光标：
        C-f     光标右(forward)
        C-b     光标左(backward)
        C-p     光标上(previous)
        C-n     光标下(next)
        C-W-f   往右一个单词 (option + right_arrow)
        C-W-b   往左一个单词 (option + left_arrow)
        C-a     光标移动到行首
        C-e     光标移动到行尾
    删除：
        C-h     删除光标左边的一个字符
        C-d     删除光标右边的一个字符
        C-W-h   删除光标左边的一个单词（option + delete）
        C-W-d   删除光标右边的一个单词（fn + option + delete）
        C-k     删除从当前光标到行尾的所有内容（这个有）
        C-u     删除从当前光标到行首的所有内容（command + backspace）
    选中单词：
         S + W + f, b 选中左右的单词


```



基于上面那套方案，采用Karabiner-Elements改键

1. 需要交换capslock和control键
2. 将组合键配置json导入到 `.config/karabiner/assets/complex_modifications`文件夹下面