# ImageSegmentor
segment remotely sensed images into meaningful regions.

This software has realized the following methods for segmentating images: graph based segmentation, quad tree segmentation, multiresolution segmentation, and two-stage segmentation, watershed, mean shift; also, mrf classification, primitive building extraction, change detection based on gradient correlation, histogram matching, intensity correlation and rosin automatic thresholding.

The release version has been tested to run successfully over windows XP, windows 7 operating systems. It is written by C++ language, compiled in Visual C++ 6.0.
# Dependencies
OpenCV 1.0 libraries are used to support some routines, such as region geometrical properties computation, morphological operations, k-means clustering. The GDAL library is used to read and write a host of image formats, *.tif, *.img, etc., and to produce vector files, such as *.shp. Both of OpenCV and GDAL are included in the package for easy compilation.

# Installation
(1) clone this package onto your computer
(2) Open the image.dsw file in the root directory in Visual C++6.0 compiler
(3) Compile and Debug. If there are linking problems, you may have to change the project settings to link libraries for GDAL and OpenCV.

More information about this package can be found at http://blog.csdn.net/pobudeyi/article/details/6074118
