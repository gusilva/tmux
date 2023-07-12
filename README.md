## TMUX

- Setup

1. install
[tmux](https://github.com/tmux/tmux/releases/tag/3.3a)

2. install tmux package manager
[tpm](https://github.com/tmux-plugins/tpm)

2. source tmux config
```
tmux source ~/.config/tmux/tmux.conf
```

- Commands
[tmux cheat sheet](https://tmuxcheatsheet.com/)

create window
```
<prefix>c
```

change window
```
<prefix>[window number]
```

change to the [n]ext window
```
<prefix>n
```

change to the [p]revious window
```
<prefix>p
```

swap window
```
<prefix>:
swap-window -s 2 -t 1
```

kill the window
```
<prefix>&
```

split pane hortizontally
```
<prefix>%
```
 
split pane vertically
```
<prefix>"
```

navigate between panes
```
<prefix>Up
<prefix>Down
<prefix>Left
<prefix>Right
```

swap panes
```
<prefix>{
<prefix>}
```

show panes numbers
```
<prefix>q
```

zoom the pane to take the full window
```
<prefix>z
```

close a pane
```
<prefix>x
```

create a new named session
```
tmux new -s my-session
```

list session outside tmux
```
tmux ls
```

list session inside tmux
```
<prefix>a
```

preview each session
```
<prefix>w
```

attach to a tmux session outside tmux
```
tmux attach
```

attach to a tmux session outside tmux by session name
```
tmux attach -t my-session
```

install package
```
<prefix>I
```

enter copy mode
```
<prefix>[
```

- Navigation

1. Install Vim Tmux Navigator
[VTN](https://github.com/christoomey/vim-tmux-navigator)


- Key bindings

