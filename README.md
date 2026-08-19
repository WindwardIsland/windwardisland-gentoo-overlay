## Purpose

This is my personal Gentoo overlay. Its main purpose is to host the latest versions of certain packages that are not available in the Portage tree yet, and also not available in any outside packaging repositories (e.g. cargo for Rust applications).

## Available Packages
As of right now, this overlay has the following packages available:
- [skalibs](https://skarnet.org/software/skalibs)
- [execline](https://skarnet.org/software/execline)
- [s6](https://skarnet.org/software/s6)
- [s6-rc](https://skarnet.org/software/s6-rc)
- [s6-linux-init](https://skarnet.org/software/s6-linux-init)
- [s6-frontend](https://skarnet.org/software/s6-frontend)

## Disclosure
This overlay is automatically updated with a script. The script *only* supports retrieving the latest versions of the packages listed above. Future support for other unrelated packages is currently undecided. 
