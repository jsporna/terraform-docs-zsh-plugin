terraform-docs-zsh-plugin
=========================

Plugin for terraform-docs adds
- autocomplete for commands 
- autocomplete for global flags
- autocomplete for command flags
- alias

# Requirements

* [terraform-docs](https://github.com/terraform-docs/terraform-docs)

# Installation

* [Oh My Zsh](#oh-my-zsh)
  
## Oh My Zsh

1. Clone repository into `${ZSH_CUSTOM}/plugins` (by default `$ZSH_CUSTOM` points to `~/.oh-my-zsh/custom`)

```sh
git clone https://github.com/jsporna/terraform-docs-zsh-plugin \
    ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/terraform-docs
```

2. Add te plugin to the list of plugins in `~/.zshrc` for Oh My Zsh to load:

```sh
plugins=(... terraform-docs)
```

3. Start new terminal session.

# Usage

* Type `terraform-docs` or `tfdocs` into your prompt and hit `TAB` to see available completion options