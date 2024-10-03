# sessions

### list sessions
tmux ls

### create brand new session
tmux new -s <name>

### attach recent session
tmux a

### attach to targeted session
tmux a -t <id>

### detach current session
prefix + d

### kill most recent session
tmux kill-session

### kill targeted recent session
tmux kill-session -t <name>

# window 

### create a new window 
prefix + c

### rename current window 
prefix + , 

### kill current window 
prefix + & 

### move to the next window
prefix + n

### move to the previous window
prefix + p

### list windows
prefix + w

# panes

### split panes
prefix + " 

### vsplit panes
prefix + %

### desplay pane indx
prefix + q

### change the size of current pane
prefix + ctrl + arrows
prefix + alt + arrows

### apply predefined pane layout
prefix + alt + len(1-5)

### kill the pane 
prefix + x


note: <C-b> // default prefix 
