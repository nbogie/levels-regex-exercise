# A multi-file regex exercise

## Context

We want to rename all of the project "levels" to be 3-digit numbers.

- level 10 becomes level 100
- level 20 becomes level 200
- ... and so on...

Note that the levels are written differently:

- sometimes as `level nn`
- sometimes as `level-nn`

The filenames themselves should also be renamed.

All of this could be done manually but it would be error-prone. (There are nearly 50 changes to be made).

## Task:

Find a way to automate the changes.

Make sure you test that the links all work at the end.

TODO: add automated tests.

## Additional task:

We want level 99 to become level 999, not level 990. (It should continue to be presented as the "last" possible level).
