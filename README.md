This is a recompilation of Sage Mathematics for the Armv6l armhf Raspberry Pi.

More info about Sage is available at www.sagemath.org

On this Github repository, there is a issue tracker.
Please do not use it for Sage-related problems, as those should be opened on the Sage trac wiki/tracker.
Instead, use it for Sage issues related to the Raspberry Pi.

The downloading and unpacking should occur on the Raspberry Pi itself.

The binary is split into multiple files.
This means that you will have to reassemble them.
In addition, to make sure of the integrity of each of the archives, a MD5 sum must be run. There is a file, md5sums, which contains the sums for each of the split files. 

To untar all of the files together (execute in the root directory of the pulled repository), run this command:

cat sage-5.8.raspi-hardfp-armv6l-Linux.tar.gz_* | tar zxvf -

To check the split files against the md5sums file, run this command:

md5sum -c md5sums

Check that it says OK for every split file.

Please report any issues with the multiple images on this repository's issue tracker, as I have not yet tested each image.


