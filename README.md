# neovim

some operation and setting of neovim

# neovim基础操作

# 普通模式下

## 光标移动

### 上下左右

- h -> 左 / j -> 下 / k -> 上 / l -> 下

### 跳行

- 向下跳4行 -> 4j

- 跳转到下一个单纯的开头 -> w
- 跳转到前一个单词的开头 -> b

- 跳转到文章最上方 -> gg
- 跳转到文章最下方 -> G

- 向下翻页 -> control+d
- 向上翻页 -> control+u

- 移动到同一行的第一个选择的字母的位置 -> f+想要移动的字符（只在同一行可以）

## 复制粘贴

- 撤销 -> u ( undo )
- 复制 -> y
- 复制下面四行的内容 -> y4j
- 复制到r的内容 -> yfr
- 复制一整个词 -> yaw ( yank all words )
- 删除 -> d
- 粘贴 -> p

# 输入模式下

- 在光标前一个字母开始输入 -> i ( insert )
- 在光标后一个字母开始输入 -> a ( append )
- 在这一行开头进行输入 -> I
- 在这一行末尾进行输入 -> A

- 改变 -> c ( change )
- 删除当前这一行进入输入模式 -> cc
- 删除下四行进入输入模式 -> c4j

# 命令模式下

- :进入命令模式（是英文输入法）

# 可视模式下

- v进入可视模式
