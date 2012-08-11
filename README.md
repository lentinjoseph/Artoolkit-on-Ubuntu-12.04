Artoolkit-on-Ubuntu-12.04
=========================

Artoolkit on Ubuntu 12.04


Reference:http://www.kameda-lab.org/_local/imagelab.tsukuba.ac.jp/ubuntu1004+opencv21/ARToolKitk/index-e.html

Clone repo.

Do patching from the inside the patchdone folder using following command

$ tar xvfz ARToolKit-2.72.1.tgz 


$ patch -p0 -d . < patch-before\ installing/artk-v4l2-2.72.1.20101003.patch 


$ cd ARToolKit 


$./Configure

1st select V4L2 3rd option
2nd  select y (X86)
3rd select n
4th select n
 


$make

$cd bin

$./simpleLite

