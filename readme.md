# A multi-file regex exercise

## Context

We have a set of files in a directory.  We want to rename all of the project "levels" to be 3-digit numbers.

So

- level 10 should become level 100
- level 20 should become level 200
- ... and so on...

Note that the levels are written inconsistently:

- sometimes as `level nn`
- sometimes as `level-nn`

We will have to find and change these level references in the text of files and in the filenames.  We should rename in both cases.

All of this could be done manually but it would be error-prone. (There are nearly 50 changes to be made).

## Task:

Find a way to automate the changes.

Make sure you test that the links all work at the end.

TODO: add automated tests.

## Additional task:

We want level 99 to become level 999, not level 990. (It should continue to be presented as the "last" possible level).
