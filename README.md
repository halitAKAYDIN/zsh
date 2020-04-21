<img src="https://raw.githubusercontent.com/halitAKAYDIN/zsh/master/zsh.png"> 

#Install
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
git clone https://github.com/bhilburn/powerlevel9k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel9k
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/nobeans/zsh-sdkman.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/sdkman
```

#Config
```
cd /tmp
git clone https://github.com/halitAKAYDIN/zsh.git
cd /zsh
cp zshrc ~/.zshrc 
```

#Color Scheme
```
bash -c  "$(wget -qO- https://git.io/vQgMr)" 
8 Enter
```
<img src="https://raw.githubusercontent.com/halitAKAYDIN/zsh/master/argonaut.jpg">
