# mac终端代理设置自用

/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"

brew install --cask visual-studio-code

code .zshrc （编辑）

export http_proxy="socks5://127.0.0.1:10808"

export https_proxy="socks5://127.0.0.1:10808"

source ~/.zshrc (重启)
