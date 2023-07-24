* build dependency: `build-essential`, `libgmp-dev`, `m4`, `zlib1g-dev`, `python3`

## how to use:

1. download

```sh
## source codes
curl -O https://gcc.gnu.org/pub/gcc/releases/gcc-7.5.0/gcc-7.5.0.tar.xz
curl -O https://gcc.gnu.org/pub/gcc/infrastructure/isl-0.18.tar.bz2
```

2. build

```sh
bash ./PKGBUILD.ubuntu
```

3. create deb file

Create DEBIAN directory, then

```sh
dpkg-deb --build --root-owner-group <dir>
```
