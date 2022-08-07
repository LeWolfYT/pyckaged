# Pyckaged

### A package manager for Python

You can use Pyckaged to manage packages for all purposes.

## Installation

Installation is simple. Just run `pip install pyckaged`.

## Usage

### Installing a package

Install a package with `pyckaged install <package>`.
If you want to install a package using another package manager, you can use `pyckaged extpac <package manager> <package>`.
You can also install packages from PyPI with `pyckaged pipinstall <package>`.

#### Supported package managers:

- [pip](https://pip.pypa.io/)
- [pacman](https://wiki.archlinux.org/index.php/Pacman)
- [apt](https://www.debian.org/doc/manuals/debian-reference/ch01.en.html)
- yum
- [dnf](https://docs.fedoraproject.org/en-US/quick-docs/dnf/)
- [brew](https://brew.sh/)
- [port](https://www.macports.org/)
- [emerge](https://wiki.gentoo.org/wiki/Emerge)

### Updating a package

Run `pyckaged update <package>` to update a package. (This is not implemented yet.)
There are also commands for pip and other package managers (`pyckaged pipupdate <package>` and `pyckaged extupdate <package manager> <package>`).
