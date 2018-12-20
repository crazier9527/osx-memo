

```shell

git config --global http.postBuffer 1048576000

# Install common software
brew cask install iterm2 && brew install zsh && brew cask install shadowsocksx-ng&&brew cask install seafile-client&&brew cask install wiznote&&brew cask install google-chrome&&brew cask install postman&&brew cask install intellij-idea&&brew cask install goland&&brew cask install pycharm&&brew cask install sublime-text&&brew cask install docker&&brew cask install typora&&brew cask install wireshark && brew cask install wireshark &&brew cask install visualvm && brew cask install wechat && brew install jadx && brew install jmeter && brew cask install baidunetdisk && brew cask install intel-power-gadget && brew install openssl && brew install --with-openssl curl && brew install --with-curl --with-openssl git && brew cask install geekbench && brew cask install qq && brew cask install vlc && brew cask install handbrake && brew cask install android-studio && brew cask install sublime-text && brew cask install jd-gui && brew cask install MySQLWorkbench && brew install axel && brew install autojump && brew install gradle && brew cask install eudic && brew install zsh-syntax-highlighting && brew cask install homebrew/cask-fonts/font-source-code-pro && brew install ffmpeg --with-chromaprint --with-fdk-aac --with-fontconfig --with-freetype --with-frei0r --with-libass --with-libbluray --with-libbs2b --with-libcaca --with-libgsm --with-libmodplug --with-libsoxr --with-libssh --with-libvidstab --with-libvorbis --with-libvpx --with-opencore-amr --with-openjpeg --with-openssl --with-opus --with-rtmpdump --with-rubberband --with-schroedinger --with-sdl2 --with-snappy --with-speex --with-tesseract --with-theora --with-tools --with-two-lame --with-wavpack --with-webp --with-x265 --with-xz --with-zeromq --with-zimg && brew install webp && brew install dex2jar && brew install wget && brew install automake && brew install media-info && brew install watch && brew install autoconf && brew install apktool && brew install nmap && brew install tree && brew install golang && brew install zsh-autosuggestions && brew install autojump && brew install fasd && brew install telnet && brew install sl && brew install cmatrix && brew install maven && brew cask install aliwangwang && brew cask install neteasemusic && brew cask install visual-studio-code && brew cask install kitematic

# Update brew cask software
brew cask install --force $(brew cask outdated | awk '{print $1}' | xargs)

# Update brew command line software
brew update && brew upgrade

```

