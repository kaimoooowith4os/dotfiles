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

5. Install rust
```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

6. Install starship
```sh
cargo install starship
```

7. Install ruby/rails
```sh
rbenv install 3.2.2
rbenv global 3.2.2
gem install rails
```
