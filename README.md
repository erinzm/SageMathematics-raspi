*Due to feedback about updated versions, watch for a new version going online soon!*

=============================================================================

##IMPORTANT:
###This repo is now *partially* **unused**.
It is only maintained temporarily for archival, wiki, and  issue tracking purposes.

###The tarball is now hosted by Dropbox,
###and can be downloaded [here](http://goo.gl/gnzoDx) (I've compressed the link using goo.gl, some computers were crashing,
###and I wanted a shorter link so you could type it into the Raspberry Pi. 
###Plus, I have analytics, so I know *how many* people download it.)


=====================================================================================

This is a recompilation of Sage Mathematics for the Armv6l armhf Raspberry Pi.
If, by any chance, you want to compile it yourself, check out the [wiki](http://github.com/ArchimedesPi/SageMathematics-raspi/wiki/)!


More info about Sage is available at www.sagemath.org

On this Github repository, there is a issue tracker.
Please do not use it for Sage-related problems, as those should be opened on the [Sage trac wiki/tracker](trac.sagemath.org).
Instead, use it for Sage issues related to the Raspberry Pi.

The downloading and unpacking should occur on the Raspberry Pi itself.
To download:

````
  cd ~
  mkdir sage-math
  cd sage-math
  wget http://goo.gl/CX2Hli
````  

To check the tarball's integrity:

````
  md5sum sage-5.8.raspi-hardfp-armv6l-Linux.tar.gz
````
or
````
  md5 sage-5.8.raspi-hardfp-armv6l-Linux.tar.gz
````

If the output matches this:
````
  b09b21311e94a31d487360e12786b953
````
Then the tarball is good.

To untar the tarball:

````
  tar zxvf sage-5.8.raspi-hardfp-armv6l-Linux.tar.gz
````

If the untarring fails, try prefixing tar with sudo - that sometimes works.
If that doesn't work, *please* post an issue!



