# Dev Container Features

## Neovim

Build Neovim from source and installs

```jsonc
{
    "image": "mcr.microsoft.com/devcontainers/base:ubuntu",
    "features": {
        "ghcr.io/seanturner026/devcontainer-features/neovim:1": {
            "version": "stable"
        }
    }
}
```

## Tmux

Build Tmux from source and installs

```jsonc
{
    "image": "mcr.microsoft.com/devcontainers/base:ubuntu",
    "features": {
        "ghcr.io/seanturner026/devcontainer-features/tmux:1": {
            "version": "latest"
        }
    }
}
```
