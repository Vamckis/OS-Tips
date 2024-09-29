# TMUX

### Session
- New Session names Vamsi: tmux new -s vamsi
- Detach session: Ctrl+B  D
- Shows all sessions: tmux ls
- Reattach to recent session: tmux a
- Reattach to a session: tmux a -t <session name>
- Kill a session: tmux kill-session -t vamsi

### Panes
- Split window Vertically: Ctrl+B %
- Split window Horizontally: Ctrl+B "
- To shift panes: Ctrl+B <Arrow keys>
- To Jump Panes: Ctrl+B Q <Number>
- To Change size of Pane: Ctrl+B Ctrl+<Alt/Arrow>
- To use predesigned style: Ctrl+B Alt+<1/2/3/4/5>

### Windows
- For new window: Ctrl+B C
- To Shift window: Ctrl+B N
- To Jump window: Ctrl+B W
- To change name of window: Ctrl+B ,

### Kill
- Kill Pane: Ctrl+B X
- Kill Window: Ctrl+B &
- Kill all sessions: tmux kill-server

 ### Copy & Paste
 - Ctrl+B [ <Arrows to move> and <Space to select>
 - Ctrl+B ]

  
