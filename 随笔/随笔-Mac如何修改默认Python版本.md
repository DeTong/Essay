执行 `cd ~/.bash_profile`  命令

如果没有就创建一个 `touch ~/.bash_profile`

`open ~/.bash_profile` 添加 python="python3的安装路径" 可以用 `which python3` 命令查看

然后关闭、保存

执行 `source ~/.bash_profile` 命令使其生效

执行 `python --version` 查看默认python版本

------

再装了anaconda之后发现替换了我之前的Python版本。既然如此那就用新的版本吧。

而且现在的终端替换为了zsh。

修改`~/.zshrc`文件。

追加`alias python="你想使用的Python版本路径"`。

即可。

`upgrade_oh_my_zsh` zsh升级命令。