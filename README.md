# True/false

> Replacements to bloated /bin/false and /bin/true coreutils

# Why

Just look how huge the binaries are for the things they
do...:

- /bin/false: `.rwxr-xr-x root root 34 KB Wed Oct 20 17:24:12 2021 /bin/false*`
- /bin/true: `.rwxr-xr-x root root 34 KB Wed Oct 20 17:24:12 2021 /bin/true*`

Like wtf, and these binaries are STRIPPED

# Contributing

- Keep this folder structure:

`src/<lang>/<compiler|any>/<arch|any>/{true|false}.<ext>`

> There can be more files if wanted/needed, but
> true.<ext> and false.<ext> should always be there

- All languages submitted must be compiled
