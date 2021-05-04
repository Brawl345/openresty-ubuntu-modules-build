OpenResty modules for Ubuntu/Debian
===================================
This repository uses GitHub Actions to build [OpenResty](https://openresty.org/en/) with the default configuration for Ubuntu/Debian (with they themselves use).

## Workflow
It does the following:

1. Clones the [openresty-packaging](https://github.com/openresty/openresty-packaging/) and modules repositories
2. Patches the `debian/rules` file to include the new modules
3. Builds OpenResty
4. Uploads the *.so files

Check out the actions tab!

## Motivation
I don't want to build OpenResty myself everytime and still want to use their apt repository so why not shift the work to GitHub? ;)
