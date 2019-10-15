# Userspace .config directory of various tools

## Powerline prompt for bash
Features:
- Command line prompt on multiple lines (two in my case). You can change at [./powerline/themes/shell/default_multiline.json](./powerline/themes/shell/default_multiline.json)
- Shows
   - Kubernetes context (thanks to Powerkube project Powerline plugin). Manage Normal/Warn/Alert colors for Kubernetes context - cluster/namespace at [./powerline/colorschemes/shell/default.json](./powerline/colorschemes/shell/default.json).
   - git branch

Example:

![image](./repo-art/screenshot_powerline-bash-powerkube.png)

### Installation

Powerline installed using pip (in my case on [Mint 19.2](https://www.linuxmint.com/start/tina/))
```
$ sudo apt install python-pip
$ pip install powerline-status powerkube

$ pip list | grep power
powerkube (0.1.3)
powerline-status (2.7)

```

```git clone https://github.com/MilanMasek/.config.git``` this repo after you get powerline
