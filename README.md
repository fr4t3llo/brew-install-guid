# brew-install-guid
Follow this guide, and Homebrew will be installed on your machine without requiring sudo privileges.



#download
```sh
cd ~
```

```sh
git clone https://github.com/Homebrew/brew homebrew
```

```sh 
mkdir -p ~/usr/local
```


# installed packaged directory
```sh
echo "export HOMEBREW_PREFIX=~/usr/local" >> ~/.zshrc
```

```sh
echo "export PATH=$PATH:~/homebrew/bin:HOMEBREW_PREFIX/bin" >> ~/.zshrc
```

```sh
echo "source ~/.zshrc"
```

# update brew
```sh
$ brew update
```
# if error

```sh 
brew update-reset
```
