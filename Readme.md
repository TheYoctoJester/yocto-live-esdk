Building and booting QEMU
=========================

- `devtool build-image` - builds the image canned in the esdk
- `runqemu nographic slirp` - runs the newly built image in qemu. nographic: we don't want X11, slirp: userspace networking only