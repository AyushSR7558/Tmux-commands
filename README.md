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

Session : A session is like a saved terminal environment that you can leave and return to anytime.