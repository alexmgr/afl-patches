# afl-patches
A set of patches to get AFL working on BSD

* `afl-as-bsd8.diff`: part of AFL 1.84b. Makes AFL work on old BSD version
* `bsd-qemu-mode.diff`: not currently part of AFL. Allows QEMU mode to work on BSD. **32 bit binaries will not work on 64 bit QEMU BSD userland**
