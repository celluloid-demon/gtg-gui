# docker test

Trying to get Getting Things GNOME gui to run from a docker container (flatpak crashes on my fedora system so attempting to use the ubuntu version from ubuntu:lunar).

## How to use:

1. run `up.sh`

## Additional Notes

- if the newly-created container immediately spins down, there was probably an errant segfault that hasn't been addressed, but could be investigated through docker logs for the container. hit `up.sh` a few times and it should run.
