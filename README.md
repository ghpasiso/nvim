# nvim
my neovim configuration

## Dependencies
### 1. install neovim
### 2. install vim-plug

### 3. clone this repo to your neovim configuration path
```bash
cd $HOME/.config
git clone https://github.com/ghpasiso/nvim.git
```

### 4. install the basic software
```bash
apt install git make cmake gcc g++ gdb ripgrep fd-find python3-pip
```

### 5. pip3 must also be installed
```
pip3 install pynvim
```

### 6. install nodjs

### 7. install yarn
```
npm -g install yarn
```
### 8. install neovim
```
npm install -g neovim
```
### 9. install clangd

### 10. open file $HOME/.config/nvim/init.vim with neovim 
```viml
:PlugInstall
```

### 11. install coc.nvim
```
cd /root/.vim/plugged/coc.nvim
yarn install
yarn build
```

### 12. install tree-sitter 
```
yarn global add tree-sitter-cli
```


