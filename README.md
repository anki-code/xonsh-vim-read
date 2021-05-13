The xonsh shell wrapper to running the command via vim read.

## Install

```python
xonsh
cd $XDG_DATA_HOME
git clone https://github.com/anki-code/xonsh-vim-read
echo 'set shell=$XDG_DATA_HOME/xonsh-vim-read/xonsh-vim-read' >> ~/.vimrc
```

## Usage

```python
vim
:read !2+2
# 4
```

## Links 
* This package was created with [xontrib cookiecutter template](https://github.com/xonsh/xontrib-cookiecutter).
