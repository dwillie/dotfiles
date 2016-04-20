DSTIL Dotfiles
==============

Bootstrap:

For Bash 4.x (modern Linux):

```
source <(curl -s https://raw.githubusercontent.com/dstil/dotfiles/master/bootstrap)
```

For Bash ~3.2 (OSX):

```
curl -s https://raw.githubusercontent.com/rimmington/dothooks/master/bootstrap > bootstrap && DOTFILES_REPOS='https://github.com/dstil/dotfiles' bash ./bootstrap; rm ./bootstrap
```

See [rimmington/dothooks](https://github.com/rimmington/dothooks) for a more general bootstrap with more options.

Utilities
--------

Run `labcheck` in a Git repository to check for compliance with lab best practices.
