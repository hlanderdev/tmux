tmux commands
-t is generally target pane/window
-t defaults to current selected pane/window if not specified
TODO: Fact check above

- tmux resize-pane
-t pane number
-L left  (always shrinks unless pane on far right)
-U up    (always shrinks unless pane on bottom)
-R right (always grows unless pane on far right)
-D down  (always grows unless pane on bottom)

pane size cannot be shorter than 1 row nor skinnier than 1 column

if there is no room to shrink neighboring pane in that direction will shrink instead, unless the pane is at an edge or the neighbor also is at minimum size
