# dotfiles
Dotfiles are managed using [chezmoi][chezmoi].

## Installation
After installing chezmoi, run
```
chezmoi init https://github.com/BLing88/dotfiles.git
chezmoi apply
```
You’ll need to define the configuration variables (see [here for details][template variables]) in ~/.config/chezmoi/chezmoi.toml. 

## Updates
Run 
```
chezmoi update
```

[chezmoi]: https://github.com/twpayne/chezmoi
[template variables]: https://github.com/twpayne/chezmoi/blob/master/docs/HOWTO.md#use-templates-to-manage-files-that-vary-from-machine-to-machine
