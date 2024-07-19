
# oh-my-zsh (oh-my-zsh)

Install (Oh-My-)ZSH plugins

## Example Usage

```json
"features": {
    "ghcr.io/winwangqi/dev-container-features/oh-my-zsh:0": {}
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| plugins | Space separated list of ZSH plugin names that will be added to .zshrc | string | - |
| omzPlugins | Space separated list of Oh-My-ZSH custom plugin Git URLs that will be cloned | string | - |
| username | For which user to setup ZSH plugins, by default uses 'remoteUser' or 'containerUser' from config | string | - |



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/winwangqi/dev-container-features/blob/main/src/oh-my-zsh/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
