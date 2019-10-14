# Local userspace .config directory 
Tools configuration for easier backup and restore purposes

## Powerline Bash prompt on two lines
Features:
- Command line prompt on multiple lines (two in my case). You can rewrite at [./powerline/themes/shell/default_multiline.json](./powerline/themes/shell/default_multiline.json)
- Shows
   - Kubernetes context
   - git branch

Example:

![image](./repo-art/screenshot-bash.png)

### Installation

Powerline installed using pip (in my case on Mint 19.2)
```
$ sudo apt install python-pip
$ pip install powerline-status powerkube
```

```git clone https://github.com/MilanMasek/.config.git``` this repo after you get powerline
