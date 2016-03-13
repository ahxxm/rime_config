# rime_config

一套不报错的配置，堪堪能用的词库，和仿系统输入法风格的皮肤。

翻页快捷键是`ctrl + v`。

![wat](https://raw.githubusercontent.com/ahxxm/rime_config/master/usage.png)

## 使用方法

### OS X

先从[官网](http://dl.bintray.com/lotem/rime/Squirrel-0.9.26.2.zip)下载发行版安装好，然后：

    rm -rf ~/Library/Rime
    git clone --depth=1 https://github.com/ahxxm/rime_config.git ~/Library/Rime

点任务栏程序图标，点Deploy，过一会儿（搞不好会）提示成功，就能用了。

### Arch Linux

这样：

    sudo pacman -S ibus-rime
    cd ~/.config/ibus
    git clone https://github.com/ahxxm/rime_config.git rime
    ibus-setup
    ibus-daemon -drx
    
然后注销，登入，在输入法里选上Rime，点部署/Deploy，过一会儿（搞不好会）提示成功，就能用了。

## 引用来源

词库：[http://tieba.baidu.com/p/3974457224](http://tieba.baidu.com/p/3974457224)

皮肤：[http://tieba.baidu.com/p/3918630308](http://tieba.baidu.com/p/3918630308)
