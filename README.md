# github.com/maximuskowalski/dotfiles

My dotfiles, managed with [`chezmoi`](https://github.com/twpayne/chezmoi).

Install them with:

    chezmoi init git@github.com:maximuskowalski/dotfiles.git
    
    

OR use `https://github.com/maximuskowalski/dotfiles.git` instead with

```
chezmoi init maximuskowalski
```



Personal secrets are stored in [1Password](https://1password.com) and you'll
need the [1Password CLI](https://developer.1password.com/docs/cli/) installed.
Login to 1Password with:

    eval $(op signin)
