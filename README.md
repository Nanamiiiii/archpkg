# archpkg
Self-hosted package repository

## Packages
| Package | Version |
| :-- | :-- |
| neovim-head | HEAD |
| skk-jisyo-emoji | `0.0.9` |
| riscv-gnu-toolchain-bin-13 | `2024.02.02` |
| riscv-gnu-toolchain-bin-10 | `2021.01.26` |
| riscv-musl-toolchain-bin-13 | `2024.02.02` |

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
