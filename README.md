# Khải's Pacman Repository

Repository of Arch Linux packages for my personal use.

## Installation

Add the following code snippet to your `/etc/pacman.conf`:

```conf
[khai]
SigLevel = Optional
Server = https://raw.github.com/KSXGitHub/pacman-repo/master/repo
```

Then, run `sudo pacman -Sy` to update repository.
