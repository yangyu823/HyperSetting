# HyperSetting

#### 1. Nerd Fonts

:octocat: https://github.com/ryanoasis/nerd-fonts

##### Option 4: Homebrew Fonts
>Best option if on macOS and want to use Homebrew.

All fonts are available via Homebrew Fonts on macOS (OS X)

````
brew tap caskroom/fonts
brew cask install font-hack-nerd-font
````

#### 2. Install ZSH

```brew install zsh zsh-completions```

######Set as default shell

```chsh -s /bin/zsh```


#### 3. Install Oh_My_ZSH

via curl

```sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"```

via wget

```sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"```
 
#### 4. Install PowerLevel9K
 
 First get the homebrew tap

```brew tap sambadevi/powerlevel9k```

Then install powerlevel9k via brew

```brew install powerlevel9k```


Themes Install for Oh_My_ZSH

```git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k```



 
 [.zshrc] file

````

ZSH_THEME="powerlevel9k/powerlevel9k"
POWERLEVEL9K_MODE='nerdfont-complete'
#------------------------------------------------------------------------#
POWERLEVEL9K_SHORTEN_DIR_LENGTH=2
POWERLEVEL9K_SHORTEN_STRATEGY="truncate_middle"
POWERLEVEL9K_OS_ICON_BACKGROUND="000"
POWERLEVEL9K_OS_ICON_FOREGROUND="none"
POWERLEVEL9K_CONTEXT_DEFAULT_BACKGROUND="006"
POWERLEVEL9K_CONTEXT_DEFAULT_FOREGROUND="000"
POWERLEVEL9K_DIR_HOME_BACKGROUND="002"
POWERLEVEL9K_DIR_HOME_FOREGROUND="000"
POWERLEVEL9K_DIR_HOME_SUBFOLDER_BACKGROUND="001"
POWERLEVEL9K_DIR_HOME_SUBFOLDER_FOREGROUND="000"
POWERLEVEL9K_NODE_VERSION_BACKGROUND="black"
POWERLEVEL9K_NODE_VERSION_FOREGROUND="007"
POWERLEVEL9K_NODE_VERSION_VISUAL_IDENTIFIER_COLOR="002"
POWERLEVEL9K_STATUS_OK_BACKGROUND="black"
POWERLEVEL9K_STATUS_OK_FOREGROUND="green"
POWERLEVEL9K_BACKGROUND_JOBS_FOREGROUND='black'
POWERLEVEL9K_BACKGROUND_JOBS_BACKGROUND='178'
POWERLEVEL9K_TIME_BACKGROUND="white"
POWERLEVEL9K_TIME_FORMAT="%D{\uf017 %H:%M \uf073 %d/%m/%y}"
POWERLEVEL9K_LEFT_PROMPT_ELEMENTS=('os_icon' 'virtualenv' 'context' 'dir' 'vcs')
POWERLEVEL9K_RIGHT_PROMPT_ELEMENTS=('node_version' 'status' 'background_jobs' 'history' 'time')
POWERLEVEL9K_LEFT_SEGMENT_SEPARATOR=$'\uE0B0'
POWERLEVEL9K_RIGHT_SEGMENT_SEPARATOR=$'\uE0B2'
#------------------------------------------------------------------------#
````

#### 3. [.hyper.js] file

````
    fontFamily: '"Hack Nerd Font","Roboto Mono for Powerline", "Meslo LG L DZ for Powerline", "Source Code Pro for Powerline", Menlo, "DejaVu Sans Mono", Consolas, "Lucida Console", monospace',
````
