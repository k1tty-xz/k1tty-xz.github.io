# Python 3.14 for jailbroken iOS

System-wide CPython 3.14 for rootful jailbroken iOS devices, built with
CPython's official iOS toolchain.

## Current package

- Rootful: `iphoneos-arm`, installed under `/usr`
- Version: `3.14.7-2`
- Console launcher: standard terminal input and output (verified on rootful device)
- Build: [GitHub Actions](https://github.com/k1tty-xz/python-ios/actions/workflows/build.yml)

Install the downloaded package with:

```sh
dpkg -i ./python3.14_3.14.7-2_iphoneos-arm_rootful.deb
/usr/bin/python3.14 --version
```

## Coming later

Rootless support remains deferred until it can be tested on a jailbroken device.
pip support is also deferred until it can be verified.

Package source: [k1tty-xz/python-ios](https://github.com/k1tty-xz/python-ios).

Add this repository to your package manager:

`https://k1tty-xz.github.io/`
