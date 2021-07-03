# CLI Dotfiles

## Installation

```shell
alias dtscli="/usr/bin/git --git-dir=$HOME/.config/cli_dotfiles/
--work-tree=$XDG_CONFIG_HOME"
git clone --bare <git-repo-url> $XDG_CONFIG_HOME/cli_dotfiles
dtscli checkout
```
