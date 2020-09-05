Process audio files with [Ardour](https://ardour.org/).

Folder `original` contains the original `.mp3` for the project.
The audio is about 6-minutes long and is about 9MB. Importing the
file into Ardour on a stereo track creates two `.wav` files, each
about 65MB.

Git ignores the `.wav` files. The idea is to treat `.wav` files
like *build* files in a programming project. The Ardour session
should contain all the information necessary to generate the
`.wav` files.
