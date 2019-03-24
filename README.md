# 386bsd0.x
Track updates to 0.1 by William Jolitz

W.I.P.

An attempt to create a disk image running https://github.com/386bsd/386bsd/tree/0.1 in an emulator.

Some self imposed and boundaries, goals and liberties:

- Use modern widely available emulators as soon as possible.

Getting the original 386bsd 0.1 to boot in emulation was done with hacked up or older versions of bochs and qemu. Ideally this should run on widely supported builds of bochs/qemu or VirtualBox or even in the browser on one of the js x86 emulators.

- Hardware free development

This repo will mostly grow by abusing the github.com text editor -> Travis CI -> gh-pages pipeline. Consequently the commit history will look horrible.

- Reproducible

By using Travis CI demonstrate this is not a one-off, and someone can use this repo as guide to build such an image.

- Trivial code

No piles of C code, just well aimed shell fu and original material
