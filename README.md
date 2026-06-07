# dotfiles

Personal dotfiles managed with [chezmoi](https://www.chezmoi.io/).

## What's included

- **starship** — prompt configuration
- **tmux** — oh-my-tmux + personal customizations
- **zsh** — oh-my-zsh based config
- **nvim** — AstroNvim v4 user configuration

## Bootstrap

```bash
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply julienchevrier
```

You'll be prompted for a profile (`personal` or `work`). The `work` profile pulls additional config from a private repo.

## Profiles

- **personal** — generic config only
- **work** — adds `.zshrc.local` and SSH config from `dotfiles-work`
