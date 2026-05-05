# Tmux-commands
- Tmux stands for Terminal multiplexer.
- Let you manage multiple terminal session in a single window.


## Use Case
- Multiple Sessions: Run several multiple session once
- Split panel: Divide the panel into vertical/horizontal session 
- Detach/Attach: Leave a program running in the background and come back later


## Useful Commands
- tmux new -s mysession : Create the session named as mysession
- "Ctrl + b" -> d: To detch from the current terminal
- tmux ls: List all the sessions
- tmux attach: -t mysession : To attach to the sesssion
- tmux kill-session -t mysession : To kill the session named mysession
- "tmux + b" -> c : Create new window
- "tmux + b" -> p : To go to previous window
- "tmux + b" -> n : To go to next window
- "tmux + b" -> w : To view all window
- "tmub + b" -> , : To rename the window

- "Ctrl + b" -> %: To have a vertical split
- "Ctrl + b" -> ": To have a horizontal split
- "Ctrl + b" -> arrow_keys : To switch between the panel
- exit -> Terminate the shell running inside panel. Panel will automatically removed
- "Ctrl + b" -> x : Tmux will ask do you want to kill the panel
- "Cntrl + b" -> press o: Move to the next panel each time you press the o
- "Ctrl + b" -> q -> any_number: Mover to the panel using the number


Session : A session is like a saved terminal environment that you can leave and return to anytime.
Pane(Panel) : A pane = a split section of your terminal inside a tmux window

Session → whole workspace
Window → like a tab
Pane → split inside a window
