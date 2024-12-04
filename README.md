# tz

`tz` lets you use `fzf` to switch tmux sessions, while inside of a tmux session.

To use it, just copy the `tz` script to somewhere in your bin.
You can get it by running...

```
curl -O 
```

Then adding the following to your `~/.tmux.conf`:

```
choice=$(echo -e "$menu" | fzf)
```


