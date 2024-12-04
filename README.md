# tz

![Demo gif](./demo.gif)

`tz` lets you use `fzf` to switch tmux sessions, while inside of a tmux session.

To use it, just copy the `tz` script to somewhere in your bin.
You can get it by running...

```
curl -O https://raw.githubusercontent.com/LukeWood/tz/refs/heads/master/tz && chmod +x tz
```

Then adding the following to your `~/.tmux.conf`:

```
bind f run-shell "{wherever you put tz}/tz"
```

After this you can run `C-b f` and get the `tz` menu to pop up.

