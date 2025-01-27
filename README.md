# old-linux

Bash is the [GNU Project's Bourne Again SHell](https://www.gnu.org/software/bash/).

Some of the older Bash sources appear to have vanished from the Internet.

The official Bash Git repository is at <https://git.savannah.gnu.org/git/bash.git>.
The oldest commit in that repo is:

```
commit 726f63884db0132f01745f1fb4465e6621088ccf
Author: Jari Aalto <jari.aalto@cante.net>
Date:   1996-08-26 18:22:31 +0000

    Imported from ../bash-1.14.7.tar.gz.
```

Bash source tarballs can be downloaded by ftp from [ftp://ftp.gnu.org/gnu/bash](ftp://ftp.gnu.org/gnu/bash),
or on this newfangled "web" thingie at [https://ftp.gnu.org/gnu/bash/](https://ftp.gnu.org/gnu/bash/).
The oldest release provided there is 1.14.7.
There are some diffs for older releases, but only going back to 1.14.1.

The [OldLinux](https://oldlinux.org/) website collects old Linux-related sources, including some old versions of bash.
They've recently (2024-02-18) migrated their old source files to GitHub.
Here are direct download links for the versions they provide:

- [bash-1.05-linux.tar.gz (1990)](https://github.com/oldlinux-web/oldlinux-files/raw/refs/heads/master/gnu/bash/bash-1.05-linux.tar.gz)
- [bash-1.13.5.tar.gz (1993)](https://github.com/oldlinux-web/oldlinux-files/raw/refs/heads/master/gnu/bash/bash-1.13.5.tar.gz)
- [bash-1.14.tar.gz (1994)](https://github.com/oldlinux-web/oldlinux-files/raw/refs/heads/master/gnu/bash/bash-1.14.tar.gz)

The 1.13.5 and 1.14 tarballs appear to be original releases.
The 1.05 tarball includes some file changes and build artifacts (object files and executables) for a build for i386 Linux,
apparently for this build referenced on [oldlinux.org](https://oldlinux.org/).

> 2004-03-23  
> Built bash 1.05 with no job control for the orignal bootimage-0.11 image file.
> The orignal bootimage-0.11 means it was compiled without any modification to the source code of kernel 0.11.
> This bootimage file rootimage-0.11.Z can be downloaded from the Learning materials directory.

Before the move to GitHub, I downloaded several files from [oldlinux.org](https://oldlinux.org/, some of which appear to be unavailable.
I've included them in this repo:

- `bash-1.05.tar` - This appears to be an original source release of Bash 1.05,
   originally from <http://www.oldlinux.org/Linux.old/bin/old/bash-1.05.tar> (dead link).
- `bash-1.05` - Directory tree unpacked from `bash-1.05.tar`.
- `bash-1.12.lx` - This is a set of diffs to Bash 1.12 for building on Linux,
  originally from <http://www.oldlinux.org/Linux.old/bin/old/bash-1.12.lx> (dead link).
  I haven't found the bash 1.12 tarball itself.

The bash 1.05 tarball's `Changelog` documents changes going back to Mon Jun 26 13:35:16 1989.
There must have been substantial development before that, but as far as I can tell it appears to be lost.

The file `bash-1.05-patc` (sic), also included in the 1.05 tarball, is a context diff from a slightly earlier version.
