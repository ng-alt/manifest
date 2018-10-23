The manifest provides the new possibility to build the binary image with
[buildroot](https://buildroot.org) and `br-external`.

The source code can be downloaded with `git-repo` repo script. After that,
the code could be compiled with the commands:

```bash
$ source build/envsetup.sh
$ lunch r6400
$ make
```

The generated binary file will be found at the directory `out/images`
with the extension `chk`, which can be flashed with router web update
page.

