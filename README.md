# Python 3.14 for jailbroken iOS

System-wide CPython 3.14 for rootful jailbroken iOS devices, built with
CPython's official iOS toolchain.

## Current package

- Rootful: `iphoneos-arm`, installed under `/usr`
- Version: `3.14.7-7`
- Console launcher: standard terminal input and output (verified on rootful device)
- Subprocess: CPython's official `_posixsubprocess` path is verified on-device
- Build: [GitHub Actions](https://github.com/k1tty-xz/python-ios/actions/workflows/build.yml)

Install the downloaded package with:

```sh
dpkg -i ./python3.14_3.14.7-7_iphoneos-arm_rootful.deb
/usr/bin/python3.14 --version
```

## Notes

- The subprocess enablement is for jailbroken iOS only and is not supported on stock iOS.
- This build has no native `readline` extension; the REPL uses CPython's fallback.
- Rootless support remains deferred until it can be tested on a jailbroken device.
- pip: bundled via CPython's official `ensurepip`; device test pending.

Package source: [k1tty-xz/python-ios](https://github.com/k1tty-xz/python-ios).

Add this repository to your package manager:

`https://k1tty-xz.github.io/`
