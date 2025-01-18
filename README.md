# dotfiles

## Install

1. [Install Homebrew](https://brew.sh/)

2. Install dependencies using Homebrew
```sh
brew bundle
```

3. Install [Oh My Zsh](https://ohmyz.sh/)
```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

4. Link dotfiles
```sh
make link
```

5. Install ruby/rails
```sh
rbenv install 3.3.5
rbenv global 3.3.5
gem install rails
```
