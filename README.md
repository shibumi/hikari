# hikari

hikari is a slick zsh configuration with special shortcuts.

![screenshot of hikari zsh](https://raw.githubusercontent.com/shibumi/hikari-zsh/master/screenshots/hikari1.png)

## Requirements
* zsh

## Optional Requirements
* zsh-syntax-highlighting
* skim
* kubectx

## Recordings

### Basic features

![basics](https://raw.githubusercontent.com/shibumi/hikari-zsh/master/recordings/basics.gif)

### Advanced features

![advanced](https://raw.githubusercontent.com/shibumi/hikari-zsh/master/recordings/advanced.gif)

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

## Overwrite configuration
Feel free to import zsh configuration before hikari via `.zshrc.pre` and
import it after hikari via `zshrc.local`.

## Additional shortcuts
### Advanced string operations
* Press `ctrl+x '` for surrounding single quotes
* Press `ctrl+x "` for surrounding double quotes
* Press `ctrl+x ;` for deleting everything inside of quotes
### Add sudo in front of every command via shortcut
* Press `ctrl+x s` for inserting sudo in front of any command
### Insert the current date into the shell
* Press `ctrl+x d` for inserting the current date
### jump after the first word to insert arguments
* Press `ctrl+x 1` to jump behind the first word to insert additional arguments
### Special behaviour with directories
* Press `ctrl+left` or `ctrl+right` to jump between full words
* Press `alt+left` or `alt+right` to jump between `/` in paths
* Press `alt+backspace` to delete until next `/` in paths
* Press `ctrl+w` to delete the whole last word
### Copy the previous typed word
* Press `ctrl+x c` for copying + inserting the last typed word
### Get last modified file
* Press `ctrl+x l` for printing the last modified file in the current directory
### skim shortcuts and completion features
* Press `ctrl+t` for listing files and folders. For example: `nvim ctrl+t`
* Press `ctrl+r` for fuzzy search history
* Press `alt+c` for fuzzy change directory

## Additional features
* upline search
* interactive comments
* background jobs
* vcs support
