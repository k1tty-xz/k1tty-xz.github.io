# Python 3.14 for jailbroken iOS

System-wide CPython 3.14 for rootful jailbroken iOS devices.

## Current package

- Rootful: `iphoneos-arm`, installed under `/usr`
- Version: `3.14.7-1`
- Build: [GitHub Actions](https://github.com/k1tty-xz/python-ios/actions/workflows/build.yml)

Install the downloaded package with:

```sh
dpkg -i ./python3.14_3.14.7-1_iphoneos-arm_rootful.deb
/usr/bin/python3.14 --version
```

## Coming later

Rootless support will be added after the rootful package has been tested on a
jailbroken device. pip support is also deferred until it can be verified.

Package source: [k1tty-xz/python-ios](https://github.com/k1tty-xz/python-ios).

Add this repository to your package manager:

`https://k1tty-xz.github.io/`
