# nvim-dotfiles
> /Users/danieltruong/.config/nvim

# Keybinds
> List of keybindings I use for nvim

# Vim 
| Keybinds  | Description |
| ------------- | ------------- |
|  dd  | Delete line  |
|  x  | Delete word  |
| d   | Cut |
| y / Y | Copy |
| p / P | Paste |
| / | Search for word |
| n / N | Navigate searched word |
| ciw | Change a word |
| gg / G | Top line of file / End line of file |
| ^ | First in line |
| $ | Last in word |
| "+y | Copy buffer ( to paste it in outside of current window) |

# tmux - Terminal
| Keybinds  | Description |
| ------------- | ------------- |
|  tmux  | Actiavte tmux ( create new session ) |
|  tmux new -s {name} | Create new session with name |
|  <Ctrl + b> + [ | Scroll |
|  <Ctrl + b> + %  | Split Pane to Right |
|  <Ctrl + b> + "  | Split Pane to Bottom |
|  <Ctrl + b> + :  | Open Command Pane |
|  :resize-window -{direction} unit  | Resize tmux window |
| <Ctrl + b> + left arrow  | Go to Left Pane  |
| <Ctrl + b> + right arrow | Go to Right Pane |
|  <Ctrl + b> + c  | New Window |
|  <Ctrl + b> + 0  | Switch to Window 0 |
|  <Ctrl + b> + ,  | Rename Window 
|  <Ctrl + b> + d  | Detach Session |
|  tmux ls  | View past sessions |
|  tmux rename-session -t {session name} {new name}  | Rename a session |
|  tmux attach - t {session name}  | Restore session |
|  tmux kill-session -t {session name}  | Kill a session |
|  tmux kill-session -a | Kill all sessions except the one using |

# TreeNerd - Folder Tree
| Keybinds  | Description |
| ------------- | ------------- |
|  <Ctrl + n>  | Open folder tree  |
| <Ctrl + t>   | Tree toggle |
| <Ctrl + f> | Tree focus |

# Barbar - Tab 
| Keybinds  | Description |
| ------------- | ------------- |
|  <Option + . >  | Next tab  |
| <Option + ,>   | Prev tab |
| <Option +  c >   | Close urrent tab |

# Telescope - Find Files
| Keybinds  | Description |
| ------------- | ------------- |
| ff | Open search for files |
| fg | Open search for words |
