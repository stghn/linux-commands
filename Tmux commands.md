# Tmux commands

## Create a session
```sh
tmux new -s <session-name>
```

## List all sessions
```sh
tmux ls
```

## Delete a session
```sh
tmux kill-session -t <session-name>
```

## Attach(Enter) a session
```sh
tmux a -t <session-name>
```

# Inside tmux
Press <kbd>Ctrl</kbd> + <kbd>b</kbd> and then do one of the followings.

## Detach(Leave) a session
<kbd>d</kbd>

## Leave and detach a session
`:kill-session`

## Scroll the screen(page up, page down)
`[` and then <kbd>Page Up</kbd> + <kbd>Page Down</kbd> 

## Useful link

[tmux Cheat Sheet](https://gist.github.com/michaellihs/b6d46fa460fa5e429ea7ee5ff8794b96)

[tmux cheatsheet](https://gist.github.com/henrik/1967800)

[Tmux 快捷键 & 速查表](https://gist.github.com/ryerh/14b7c24dfd623ef8edc7)