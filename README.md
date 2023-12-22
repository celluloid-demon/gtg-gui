# docker test

Trying to get Getting Things GNOME gui to run from a docker container (flatpak crashes on my fedora system so attempting to use the ubuntu version from ubuntu:lunar).

## How to use:

1. Create $HOME/Documents/GTG/tmp, symlink to newly-created `tmp` from project root.
2. Run `up.sh`

## Additional Notes

- If the newly-created container immediately spins down (read: the GTG application window doesn't even pop up), there was probably an errant segfault that hasn't been addressed, but could be investigated through docker logs for the container. Hit `up.sh` a few times and it should run.
