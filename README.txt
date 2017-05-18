These are files I generated from Octave to get the Piotr's Computer Vision Matlab Toolbox working.
The toolbox has to be downloaded from https://pdollar.github.io/toolbox/ and referenced and used as specified there.

I am not the author of the toolbox and therefore, all the files that belong to the toolbox are absent from this repo. I kept the structure though so you can manually add each file to its proper location.

The only file that is in the toolbox and that you need to overwrite is the wrapper.hpp file (channels/private). There is just 1 or 2 lines changed.

This repo has been created with the only goal of helping people struggling to use this beautiful toolbox with Octave :)
I am currently contacting the author of the toolbox to see how modifications can be brought for Octave users.

If one wants to try to create these files by himself/herself, please refer to http://stackoverflow.com/questions/40896162/mex-file-building-with-octave-issue-with-wrappers

I still believe that the best option is to generate these files by yourself :)

Configuration when files generated:
Octave 4.2.0
Configured for "x86_64-w64-mingw32"
Windows10 (64 bits)