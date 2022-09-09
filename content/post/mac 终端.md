---
title: "mac 终端"
date: 2022-09-09T13:51:46+08:00
auth: "wming"
---

### iTerm

1.  安装终端

    ```sh
    brew install --cask iterm2
    ```

2.  安装 oh my zsh

    ```sh
    sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    ```

3.  安装插件 zsh-autosuggestions

    ```sh
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```

    添加插件到配制文件 '.zshrc'

    ```sh
    source ~/.zsh/zsh-autosuggestions/zsh-autosuggestions.zsh
    ```

4.  美化终端：Powerlevel10k

    安装：Powerlevel10k

    ```sh
    git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
    ```

    在配制文件`.zshrc`中设置 `ZSH_THEME="powerlevel10k/powerlevel10k"`
