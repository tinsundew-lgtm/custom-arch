# Arch by Tin

Custom Arch Linux live ISO built with [archiso](https://wiki.archlinux.org/title/Archiso) (based on the official `releng` profile).

- ISO: `arch-by-tin-v1-x86_64.iso`
- Boot the ISO (UEFI) and run `archinst` for the TUI installer.

## Build

GitHub Actions builds the ISO on every push (Actions tab -> artifact `arch-by-tin-iso`).
Pushing a tag like `v1` also publishes the ISO as a GitHub Release.

Locally on Arch:

```bash
sudo mkarchiso -v -w /tmp/archiso-work -o out .
```
