# Mac Setup
I use the following setup on my Mac for software development. 

## Terminal Setup
- [ ] iTerm2
- [ ] oh-my-zsh
- [ ] Home Brew
- [ ] Python3 (with Brew)
- [ ] OrbStack (instead of Docker Desktop)
- [GitHub - zsh-users/zsh-autosuggestions: Fish-like autosuggestions for zsh](https://github.com/zsh-users/zsh-autosuggestions), Install Instructions: [zsh-autosuggestions/INSTALL.md at master · zsh-users/zsh-autosuggestions · GitHub](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh)
  1. `brew install zsh-autosuggestions`
  2. `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git`
  3. `echo "source ${(q-)PWD}/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc`
- [ ] [GitHub - zsh-users/zsh-syntax-highlighting: Fish shell like syntax highlighting for Zsh.](https://github.com/zsh-users/zsh-syntax-highlighting) 
  - [ ] `brew install zsh-syntax-highlighting`
- [ ]  AWS CLI
- [ ] sdkman
  - [ ] Java
  - [ ] Gradle
  - [ ] Maven

### Rust Powered Utilities 
[7 Awesome Rust-powered Command-line Utilities - Towards Data Science](https://towardsdatascience.com/awesome-rust-powered-command-line-utilities-b5359c38692)

- [ ] starship [Starship: Cross-Shell Prompt](https://starship.rs/)
  - [ ] config: [Configuration | Starship](https://starship.rs/config/)
- [ ] ripgrep [Releases · BurntSushi/ripgrep · GitHub](https://github.com/BurntSushi/ripgrep/releases)
- [ ] bat [GitHub - sharkdp/bat: A cat(1) clone with wings.](https://github.com/sharkdp/bat)
- [ ] exa https://github.com/ogham/exa
- [ ] fd https://github.com/sharkdp/fd
- [ ] procs https://github.com/dalance/procs
- [ ] hub [hub · an extension to command-line git](https://hub.github.com/)
- [ ] git-trim[GitHub - foriequal0/git-trim: Automatically trims your branches whose tracking remote refs are merged or stray](https://github.com/foriequal0/git-trim)
- [ ] jq [GitHub - stedolan/jq: Command-line JSON processor](https://github.com/stedolan/jq)  `brew install jq`
- [ ] brew install dust (du alternative)
- [ ] brew install ouch (compression)
- [ ] brew install sd (better sed)
- [ ] brew install jq (json parson)
- [ ] [zsh-syntax-highlighting/INSTALL.md at master · zsh-users/zsh-syntax-highlighting · GitHub](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md) `brew install zsh-syntax-highlighting`
- [ ] GitHub - jkfran/killport: A command-line tool to easily kill processes running on a specified port. https://github.com/jkfran/killport `brew install killport`

## Applications
- [ ] Brave Browser
  * [How to disable two finger swipe navigation - Brave Feature Requests - Brave Community](https://community.brave.com/t/how-to-disable-two-finger-swipe-navigation/94640)
  * `defaults write com.brave.Browser AppleEnableSwipeNavigateWithScrolls -bool FALSE`
  * Then restart Brave.  You can also check the current config with: `defaults read com.brave.Browser`
  * I haven’t tried it yet but I’m 99% sure you enable the gesture with: `defaults write com.brave.Browser AppleEnableSwipeNavigateWithScrolls -bool TRUE`
- [ ] Bitwarden [Open Source Password Management Solutions | Bitwarden](https://bitwarden.com/#download)
- [ ] Warp: IDE-like terminal [Warp](https://app.warp.dev/get_warp)
- [ ] Hurl.dev
- [ ] Sublime Text
- [ ] VPN Client
- [ ] DB Visualizer or DBeaver
- [ ] Idea
- [ ] VSCode
- [ ] Spark app/Spark Desktop
- [ ] Things
- [ ] Bear
- [ ] Postman
- [ ] Zoom
- [ ] Spark Mail App
- [ ] MS Outlook
- [ ] MS Word
- [ ] MS Excel
- [ ] MS Loop
- [ ] Android Developer Studio Preview
- [ ] Rectangle (Mac window manager)

## Productivity
- [ ] Cultured Code Things 3
- [ ] Bear Notes App
