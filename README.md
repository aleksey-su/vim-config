# Vim config

1) Install [powerline-fonts](https://github.com/Lokaltog/powerline-fonts) for vim-airline

2) Install Vundle plugin
```bash
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

3) Install CtrlP plugin
```bash
git clone https://github.com/ctrlpvim/ctrlp.vim.git ~/.vim/bundle/ctrlp.vim
```

4) Clone repository somewhere and copy settings:
```bash
git clone https://github.com/aleksey-su/vim-config.git ~/Downloads/vim-config/
cp -r ~/Downloads/vim-config/vim/* ~/.vim/
mv ~/Downloads/vim-config/vim/.vimrc ~/
```

1) Install python requirements
```bash
pip install -r ~/Downloads/vim-config/req.txt
```

5) Run VIM and enter:
```bash
:helptags ~/.vim/bundle/ctrlp.vim/doc
:PluginInstall
```

6) Restart VIM

