# Like dotfiles, but system-wide

# How to use

- This is nushell, but can easily be transferred to another shell
- Get arlohb/dotfiles first, so the etc alias already exists
- `sudo bash -c 'echo ".cfg" >> .gitignore'`
  - This could probably be done in nushell, but the in-built commands seem to be quite limited as sudo
- `git clone --bare https://github.com/arlohb/etc /etc/.cfg`
- `etc checkout`
- `etc config --local status.showUntrackedFiles no`

