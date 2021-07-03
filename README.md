# CLI Dotfiles

## Installation

```shell
alias dtscli="/usr/bin/git --git-dir=$XDG_CONFIG_HOME/cli_dotfiles/ --work-tree=$XDG_CONFIG_HOME"
git clone --bare <git-repo-url> $XDG_CONFIG_HOME/cli_dotfiles
dtscli checkout
```
