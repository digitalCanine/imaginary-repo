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

- **imaginary-angel** v1.0 - System guardian and maintenance tool

## Updating Packages

To update packages in this repository, upload new package files to the "packages" release tag along with updated database files (`imaginary.db.tar.gz`, `imaginary.files.tar.gz`).
