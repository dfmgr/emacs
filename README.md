## emacs  
  
An extensible, customizable, free/libre text editor  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/emacs/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install emacs-nox clang ripgrep fd-find
```  

Fedora Based:

```shell
yum install emacs-nox clang ripgrep fd-find
```  

Arch Based:

```shell
pacman -S emacs-nox clang ripgrep fd
```  

MacOS:  

```shell
brew install emacs git clang ripgrep fd coreutils
```
  
```shell
mv -fv "$HOME/.config/emacs" "$HOME/.config/emacs.bak"
git clone https://github.com/hlissner/doom-emacs "$HOME/.emacs.d"
git clone https://github.com/dfmgr/emacs "$HOME/.config/doom"
ln -sf "$HOME/.config/doom" "$HOME/.doom.d"
"$HOME/.emacs.d/bin/doom" install
"$HOME/.emacs.d/bin/doom" refresh
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/emacs" target="_blank" rel="noopener noreferrer">emacs wiki</a>  |  
  <a href="https://www.gnu.org/software/emacs" target="_blank" rel="noopener noreferrer">emacs site</a>  |  
  <a href="https://github.com/hlissner/doom-emacs" target="_blank" rel="noopener noreferrer">emacs doom site</a>
</p>  
