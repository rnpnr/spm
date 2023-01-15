# spm - simple password manager

spm is a single fully POSIX shell compliant script utilizing gpg2(1) in
combination with basic tools such as find(1) and tree(1).

Passwords are stored as [PGP](https://gnupg.org) encrypted files with
directories funtioning as (sub)groups.

spm reads/writes passwords via standard input/output allowing you to build
flexible and powerful management tools.

Refer to the manual page for various examples or read its source code to see
how it works.

## HISTORY
spm started as [tpm](https://github.com/nmeum/tpm) fork.

This repo is a fork from the original since it has 404ed.
