## emacs

An extensible, customizable, free/libre text editor

Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/emacs/raw/master/install.sh)"
```
Manual install:

requires:
```
apt install emacs-nox clang ripgrep fd-find
```
```
yum install emacs-nox clang ripgrep fd-find
```
```
pacman -S clang emacs-nox ripgrep fd
```
```
brew install git clang ripgrep fd coreutils
```

```
mv -fv "$HOME/.config/emacs" "$HOME/.config/emacs.bak"
git clone https://github.com/hlissner/doom-emacs "$HOME/.emacs.d"
git clone https://github.com/dfmgr/emacs "$HOME/.config/doom"
ln -sf "$HOME/.config/doom" "$HOME/.doom.d"
"$HOME/.emacs.d/bin/doom" install
"$HOME/.emacs.d/bin/doom" refresh

```


<p align=center>
  <a href="https://wiki.archlinux.org/index.php/emacs" target="_blank">emacs wiki</a>   |
  <a href="https://www.gnu.org/software/emacs/" target="_blank">emacs site</a>   |
  <a href="https://github.com/hlissner/doom-emacs" target="_blank">emacs doom site</a>
</p>
