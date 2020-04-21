<img src="https://raw.githubusercontent.com/halitAKAYDIN/zsh/master/zsh.png"> 

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
git clone https://github.com/bhilburn/powerlevel9k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel9k
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/nobeans/zsh-sdkman.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/sdkman

cd /tmp
git clone https://github.com/halitAKAYDIN/zsh.git
cd /zsh
cp zshrc ~/.zshrc 
```
