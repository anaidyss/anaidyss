```text
       _     __               
  ____ _____  ____ _(_)___/ /_  ____________
 / __ `/ __ \/ __ `/ / __  / / / / ___/ ___/
/ /_/ / / / / /_/ / / /_/ / /_/ (__  |__  ) 
\__,_/_/ /_/\__,_/_/\__,_/\__, /____/____/  
                         /____/             
```

andrey klein. russia. bauman lyceum + beihang university.

i dig into the parts of linux that live under the desktop: wayland
protocols, compositors, session plumbing. python, some c, too much bash.

## projects

### [veil](https://github.com/anaidyss/veil)

a lockscreen for niri on ext-session-lock-v1, in pure python
(pywayland + pillow + PAM). the compositor holds the lock session, so
kill won't save you. fake audit log at the bottom because it looks cool.

<p align="center">
  <img src="https://raw.githubusercontent.com/anaidyss/veil/main/assets/demo.gif" alt="veil in action" width="640" />
</p>

### [kb_macro](https://github.com/anaidyss/kb_macro)

global keyboard macro recorder in one python file. evdev grabs your
keyboards, uinput replays them at 2x. works everywhere: terminal,
browser, games. `Ctrl+Alt+R` to record, `Ctrl+Alt+P` to play.

## setup

niri + hyprland, fedora, jetbrains mono everywhere. dotfiles are private
until i stop breaking them weekly.

email is in git log if you need me.
