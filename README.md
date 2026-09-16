<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=1000&color=B8BB26&center=true&vCenter=true&width=820&lines=%24+whoami+%E2%86%92+andrey+klein;student+%40+bauman+lyceum+%2B+beihang+university;cat+veil.py+%23+wayland+lockscreen+in+pure+python" alt="$ whoami" />
</p>

```text
       _     __               
  ____ _____  ____ _(_)___/ /_  ____________
 / __ `/ __ \/ __ `/ / __  / / / / ___/ ___/
/ /_/ / / / / /_/ / / /_/ / /_/ (__  |__  ) 
\__,_/_/ /_/\__,_/_/\__,_/\__, /____/____/  
                         /____/             
```

```text
┌──(anaidyss@github:~)
└─$ cat identity.json
```

```json
{
  "name": "Andrey Klein",
  "location": "Russia",
  "education": ["Bauman Lyceum", "Beihang University"],
  "focus": ["linux internals", "wayland protocols", "python", "c"],
  "status": "learning in public"
}
```

```text
└─$ ls ~/projects --sort=first
drwxr-xr-x  veil/
```

### [veil](https://github.com/anaidyss/veil) — first project

локскрин для wayland (niri) на `ext-session-lock-v1`, написан с нуля на чистом python.

```text
└─$ veil-lock --explain
```

- python + pywayland, кадры через pillow (shm/memfd), пароль через PAM
- сессию держит композитор — Ctrl+C и kill не помогут
- на экране: ascii-арт, часы, cpu/ram, фейковый «аудит», палитра gruvbox

```text
└─$ ./stack --list
```

![python](https://img.shields.io/badge/python-37393E?style=flat-square&logo=python&logoColor=B8BB26)
![c](https://img.shields.io/badge/c-37393E?style=flat-square&logo=c&logoColor=B8BB26)
![bash](https://img.shields.io/badge/bash-37393E?style=flat-square&logo=gnubash&logoColor=B8BB26)
![wayland](https://img.shields.io/badge/wayland-37393E?style=flat-square&logo=wayland&logoColor=B8BB26)
![linux](https://img.shields.io/badge/linux-37393E?style=flat-square&logo=linux&logoColor=B8BB26)

```text
┌──(anaidyss@github:~)
└─$ ./connect --exit 0
```
