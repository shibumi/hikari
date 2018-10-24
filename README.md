# hikari-zsh
Hikari ZSH - A pure and minimalistic zsh with special shortcuts

![screenshot of hikari zsh](https://raw.githubusercontent.com/shibumi/hikari-zsh/master/screenshots/hikari1.png)

## Requirements
* zsh
* zsh-syntax-highlighting

## Installation
Just copy the `zshrc` file in your home or include it via `source <path to hikari zshrc file>`

## Visual Features
* VCS information via `zsh vcs_info`
* read-only directory warning (red path instead of blue)
* error code visualization (only green and red)
* hostname color randomization
* username colorization (normal users are green, root is red)
* syntax highlighting via zsh-syntax-highlighting
* command completion via parts of grml zsh

## Additional settings
Checkout the `setopts` part in the `zshrc`. One of the best features:

## Additional shortcuts
### Advanced string operations
* Press `CTRL+x '` for surrounding single quotes
* Press `CTRL+x "` for surrounding double quotes
* Press `CTRL+x ;` for deleting everything inside of quotes
[![asciicast](https://asciinema.org/a/vnGmAJIv4kAzhABllPZg2q6TI.png)](https://asciinema.org/a/vnGmAJIv4kAzhABllPZg2q6TI)
### Add sudo in front of every command via shortcut
* Press `CTRL+x s` for inserting sudo in front of any command
[![asciicast](https://asciinema.org/a/Vepjm96uUX1Qw8PfgKlze76ZM.png)](https://asciinema.org/a/Vepjm96uUX1Qw8PfgKlze76ZM)
### Insert the current date into the shell
* Press `CTRL+x d` for inserting the current date
[![asciicast](https://asciinema.org/a/Xwiwj2bFvq8wK14K5pd6UWSLP.png)](https://asciinema.org/a/Xwiwj2bFvq8wK14K5pd6UWSLP)
### jump after the first word to insert arguments
* Press `CTRL+x 1` to jump behind the first word to insert additional arguments
[![asciicast](https://asciinema.org/a/DUwbeOhCmLH60Ixqs1y3vyovB.png)](https://asciinema.org/a/DUwbeOhCmLH60Ixqs1y3vyovB)
### Special behaviour with directories
* Press `CTRL+Left` or `CTRL+Right` to jump between full words
* Press `ALT+Left` or `ALT+Right` to jump between `/` in paths
* Press `ALT+Backspace` to delete until next `/` in paths
* Press `CTRL+w` to delete the whole last word
[![asciicast](https://asciinema.org/a/5GRBxafdd68JaxcILppAnb5UW.png)](https://asciinema.org/a/5GRBxafdd68JaxcILppAnb5UW)

### Additional grml features
* upline search
* interactive comments
* ...
