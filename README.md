# brew-install-guid
Follow this guide, and Homebrew will be installed on your machine without requiring sudo privileges.



#download
```cd ~```
```git clone https://github.com/Homebrew/brew homebrew```
```mkdir -p ~/usr/local```


# installed packaged directory
```sh echo "export HOMEBREW_PREFIX=~/usr/local" >> ~/.zshrc```
```sh echo "export PATH=$PATH:~/homebrew/bin:HOMEBREW_PREFIX/bin" >> ~/.zshrc```
# update brew
$ brew update
# if error

```brew update-reset```
