# vimistifabulous

# This is my vim setup on Ubuntu.

To use just copy ".vimrc" file to your home directory and follow the step

below.

**Requirement:**

- Vim v8.1.2269 minimum with python 3 support
- git
- powerline
- powerline-fonts
- ansible-lint
- yamllint

1. Install the following packages to make sure the YCM framework can build


```
apt install build-essential cmake vim-nox python3-dev
```

- Install mono-complete, go, node, java and npm

```
apt install mono-complete golang nodejs openjdk-17-jdk openjdk-17-jre npm
```

2. Install vim-plug:

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
  https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

```
3. Start Vim launch plugin installation

```
:PlugInstall

```
4. Compile YCM framework

```
cd ~/.vim/plugged/YouCompleteMe/

python3 install.py --all

```
