reaper-test
===========

This is a project using [REAPER](https://reaper.fm) with `git`.

REAPER is digital audio workstation software. Its project files (`.rpp`), it
turns out, are just text files. Much of the information stored in the file can
be edited using a text editor. Thus it would seem that using `git` as a VCS for REAPER projects is feasible, as one would easily be able to see the actual
changes to the `.rpp` files (binary files such as recordings and samples are
another matter).

The actual project should be simple but should also use some of REAPER's
features:
- Recording audio and MIDI
- Multiple takes and tracks
- Effects and plugins
