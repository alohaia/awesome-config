# 此仓库由 "GNU与Linux技术分享" 腾讯 QQ 群群员创建，如果你也想加入 QQ 群那就快来吧!

**一群: 823167016** </br>
**二群: 466898428**

### 欢迎在这里分享你的配置文件!

#### 注意事项
- 如果可以排序，请尽量排序，Emacs 用户开启 markdown-mode 后可以使用 "C-c C-c ^" 排序
- Emacs 表格格式无法对齐请设置等高等宽字体，例如 Iosevka，配置例子:
  ```emacs-lisp
  (if (fontp (font-spec
				   :name "Iosevka"
				   :style "Regular"
				   )) 
		   (set-face-attribute 'default nil 
							   :font (font-spec 
									  :name "Iosevka"
									  :style "Regular"
									  :size 20)) 
		 (message "无法找到Iosevka Regular字体，你可以更换其他字体或安装它让这条消息消失.")
  ```
- Vim 用户请使用以下命令 (COMMAND) 以提升编辑时的体验 (如在编辑时临时开关请自行加上冒号) 最好在编辑完成后使用 [vim-table-mode](https://github.com/dhruvasagar/vim-table-mode) 进行表格体的优化
```vim
set wrap   " 开启自动换行
set nowrap " 关闭自动换行
```

| GitHub                                        | QQ 群名片    | 博客                                                              | dotfiles                                                     | vim                                                 | emacs                                                                                                                                | 介绍                                                                                                                                                                                                                                        |
|-----------------------------------------------|--------------|-------------------------------------------------------------------|--------------------------------------------------------------|-----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Augists](https://github.com/Augists)         | Augists      | [Augists](https://www.augists.top)                                | [dotfiles](https://github.com/Augists/dotfiles)              | [ZDCZ-vimrc](https://github.com/Augists/ZDCZ-vimrc) | NULL                                                                                                                                 | vimrc 配置，基于 **macOS 10.15**, vim 无自动补全，其他已经成熟; dotfiles 中为 oh-my-zsh 和 ranger 配置；欢迎造访个人博客，不定期更新学习笔记、对一些事情的思考、经验分享总结等                                                              |
| [ChunjieShan](https://github.com/ChunjieShan) | 单胖         | NULL                                                              | [.config](https://github.com/ChunjieShan/.config)            | [PangVim](https://github.com/ChunjieShan/PangVim)   | NULL                                                                                                                                 | 我的 config 文件中包括我的 dwm，st，scripts, ranger 等日常工作配置，同时包含我根据 CW，ThinkVim 和自己的使用习惯配置的 NeoVim 配置                                                                                                          |
| [Dimerbone](https://github.com/Dimerbone)     | 思钱想厚     | [DiBlog](https://dimerbone.github.io)                             | [dotfiles](https://github.com/dimerbone/Origin)              | [vim](https://github.com/dimerbone/Origin)          | NULL                                                                                                                                 | Origin Repo 中包含适用于 Arch 系的 i3、polybar、ranger、vim、rofi、dunst 等配置                                                                                                                                                             |
| [EvanMeek](https://github.com/EvanMeek)       | EvanMeek     | [我不会编程的博客](https://evanmeek.github.io)                    | [dotfiles](https://github.com/EvanMeek/dotfiles)             | NULL                                                | [doom-emacs](https://github.com/EvanMeek/dotfiles/tree/master/doom.d) [Evan-Emacs](https://github.com/EvanMeek/.emacs.d "EvanEmacs") | dotfiles 中包含 alacritty、fish shell、fcitx、i3wm、polybar、rofi 等配置                                                                                                                                                                    |
| [Innei](https://github.com/Innei)             | Innei        | [静之林](https://shizuri.net)                                     | [dotfiles](https://github.com/innei/dotfiles)                | [nvim](https://github.com/innei/nvim)               | NULL                                                                                                                                 | neovim 配置，dotfiles 中包含 zsh, fzf, git config, tmux                                                                                                                                                                                     |
| [KiteAB](https://github.com/KiteAB)           | KiteAB       | [KiteAB's Blog](https://kiteab.github.io)                         | [dotfiles](https://github.com/KiteAB/.config)                | [nvim](https://github.com/KiteAB/nvim)              | NULL                                                                                                                                 | 适用于 Arch Linux 的配置文件                                                                                                                                                                                                                |
| [UniqueDing](https://github.com/UniqueDing)   | 回忆心酸的痛 | [uniqueding](http://uniqueding.cn)                                | [dotfiles](https://github.com/UniqueDing/linux-config-files) | NULL                                                | NULL                                                                                                                                 | dotfiles 中有 ranger、i3、fish、vim (dwm、st、dmenu)等配置                                                                                                                                                                                  |
| [KyleJKC](https://github.com/KyleJKC)         | KyleJKC      | [啥也没有的博客](https://kylejkc.github.io)                       | NULL                                                         | [Neovim](https://github.com/KyleJKC/nvim)           | NULL                                                                                                                                 | 一个及其现代好用的 Neovim 配置                                                                                                                                                                                                              |
| [vritser](https://github.com/vritser)         | vritser      | [半斤八两](https://vritser.github.io)                             | [dotfiles](https://github.com/vritser/dotfiles)              | NULL                                                | [Emacs](https://github.com/vritser/.emacs.d)                                                                                         | macOS 平台, Hammerspoon 做窗口管理, 键盘布局 Dvorak 配合 Emacs [xah-fly-keys](http://ergoemacs.org/misc/xah-fly-keys_tutorial.html)                                                                                                         |
| [logicskky](https://github.com/logicskky)     | logicskky    | [LogicSkky's Blog](https://logicskky.github.io)                   | [.config](https://github.com/logicskky/.config)              | [nvim](https://github.com/logicskky/nvim)           | [.emacs.d](https://github.com/logicskky/.emacs.d)                                                                                    | .config 中有 awesome、alacritty、ranger、dwm、st、dmenu 等配置                                                                                                                                                                              |
| [VainJoker](https://github.com/vainjoker)     | Vain Joker   | [Nothing](http://vainjoker.cn)                                    | [dotfiles](https://github.com/vainjoker/myconfig)            | [Myivm](https://github.com/vainjoker/Myvim)         | [MyEmacs](https://github.com/vainjoker/MyEamcs)                                                                                      | 一些好玩的东西（dwm, st, emacs, vim, rime, 好看的字体及其对应的自动化部署脚本                                                                                                                                                               |
| [chitang233](https://github.com/chitang233)   | Chi_Tang     | [池塘の小站](https://chitang233.github.io)                        | NULL                                                         | NULL                                                | NULL                                                                                                                                 | 不定时在博客分享一些好玩的东西                                                                                                                                                                                                              |
| [SpringHan](https://github.com/SpringHan)     | SpringHan    | 正在制作                                                          | [config](https://github.com/SpringHan/config)                | [nvim](https://github.com/SpringHan/nvim)           | [.emacs.d](https://github.com/SpringHan/.emacs.d)                                                                                     | config 中包括 ranger, lazygit 等配置。nvim 是我自己慢慢配置的，我给他加上了 FloatTerminal 的可自定义的功能 (可直接调用函数)，另外还有一些我自己写的插件。.emacs.d 里也是我自己配置的，目前只写了一些，今后会慢慢补充，每天提交一个 commit。 |
| [KerrLiu](https://github.com/KerrLiu)         | Kerr         | NULL                                                              | [dotfile](https://github.com/KerrLiu/dotfile)                | NULL                                                | NULL                                                                                                                                 | 极端的配置文件, 建议阅读, 不建议使用                                                                                                                                                                                                        |
| [alohaia](https://github.com/alohaia)         | aloha        | [Aloha's Blog](https://daisilia.com)（主要是一些医学相关的内容） | NULL                                                         | [nvimcfg](https://github.com/alohaia/nvimcfg)       | NULL                                                                                                                                 | 用 Lua 写的 NeoVim 配置，内置 packer，使用原生 LSP client，不过我平时主要还是用我自己写的 [hugowiki.nvim](https://github.com/alohaia/hugowiki.nvim) 写写博客                                                                                  |
