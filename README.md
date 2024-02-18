# archpkg
Self-hosted package repository

## Packages
- neovim-head

## How to Use
1. Add to `/etc/pacman.conf`
   ```
   [myuurepo]
   Server=https://pkg.myuu.dev/archlinux/$arch
   ```
2. Register key
   ```
   sudo pacman-key --recv-keys 8F2CA5A0068E9627
   sudo pacman-key --lsign-key 8F2CA5A0068E9627
   ```
