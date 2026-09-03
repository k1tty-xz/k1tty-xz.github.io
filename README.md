# CPython 3.14 for jailbroken iOS

Package repository for the rootful CPython build from
[k1tty-xz/python-ios](https://github.com/k1tty-xz/python-ios).

## Current package

- Version: `3.14.7-8`
- Architecture: `iphoneos-arm`
- Prefix: `/usr`
- Target: arm64 and arm64e jailbroken iOS devices
- Includes the standard library, subprocess support, and pip

The build and feed checks passed. This revision awaits a rootful device
regression test.

## Install

Add this source to your package manager:

`https://k1tty-xz.github.io/`

Then install `python3.14`. Start Python with `python3` and use pip with
`python3 -m pip`.

Rootless packaging and the optional `readline` extension are not included yet.
