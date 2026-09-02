# Imaginary Linux Repository

Official package repository for Imaginary Linux.

## Usage

Add to `/etc/pacman.conf`:

```
[imaginary]
SigLevel = Optional TrustAll
Server = https://github.com/digitalcanine/imaginary-repo/releases/download/packages
```

Then run:

```bash
sudo pacman -Sy
sudo pacman -S imaginary-angel
```

## Current Packages

- **imaginary-angel** v1.0.2 - System guardian and maintenance tool
- **imaginary-release** - Script that automatically changes the release of Imaginary Linux
