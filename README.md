The manifest provides the new possibility to build the binary image with
[buildroot](https://buildroot.org) and its `br-external`.

The source code can be downloaded with `git-repo` repo script. After that,
the code could be compiled with the commands:

```bash
$ source build/envsetup.sh
$ lunch r7000
$ make
```

The generated binary file will be found at the directory `out/r6300v2/images`
with the extension both `chk` and `trx`. The `chk` file can be used to update
official firmware to merlin or flash via TFTP via TTL, and the `trx` one can
be used to upgrade the firmware.

