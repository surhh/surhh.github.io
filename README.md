# Welcome to nFITSview page!

The latest version (2.9) of nFITSview for Windows 64-bit to download:

[nfitsview2_9-setup-x64.exe](https://github.com/surhh/nfitsview/releases/download/v2.9/nfitsview2_9-setup-x64.exe)

The latest version (2.9) of nFITSview for Linux 64-bit (Debian-based) to download: 

[nfitsview2_9-x64.deb](https://github.com/surhh/nfitsview/releases/download/v2.9/nfitsview2_9-x64.deb)

The dependencies for installing in Linux are:

libboost-iostreams1.74.0 (>= 1.74.0), libc6 (>= 2.34), libgcc-s1 (>= 3.0), libpng16-16 (>= 1.6.2-1)

libqt5core5a (>= 5.15.1), libqt5gui5 (>= 5.0.2), libqt5gui5-gles (>= 5.0.2), libqt5widgets5 (>= 5.15.1), libstdc++6 (>= 11)

# About nFITSview  (next FITS viewer)
nFITSview - A user-friendly FITS image viewer

Currently nFITSview supports the following formats and features:

-    8-bit images
-    16-bit integer images
-    32-bit floating point and integer images
-    64-bit floating point and integer images
-    Exporting image HDUs as PNG/TIFF/JPEG/BMP files
-    Bulk exporting of all image HDUs as PNG files
-    RGB gamma correction, grayscale and "Eye Comfort" filters
-    Filtering by pixel threshold value
-    Image zoom in/out
-    HDU header syntax view
-    Raw data hex preview
-    Both regular and compressed (.fz) FITS files are supported
-    Command line exporting of FITS file  (see -h, -e command line switches)
     
     *Note: the console output is not visible on Windows platform. The command line 
     supports image exporting only in "Original" mapping mode.*

    
# How to build under Linux

The original development of nFITSview is done under Linux, so the easiest and the fastest way to build is under Linux.

- just build in Qt Creator. 
- it should be also possible to build using CMake from the command line.

# How to build under Windows

Normally there is no need to build under Windows as the install package is provided. 
Anyway, for building under Windows one would need to download/install/build all the dependencies (boost, zlib, libpng), then fix the
corresponding pathes for the libraries in the CMakeLists.txt file and then build the project using Qt Creator.


# Screenshots

![nfitsview2_9_screenshot_1](https://github.com/surhh/nfitsview/assets/109148999/3a671fbb-c7b3-4363-b88b-eb063e690e86)

![nfitsview2_9_screenshot_2](https://github.com/surhh/nfitsview/assets/109148999/b3db3e6a-717f-4a40-8009-990f974f9d5e)

![nfitsview2_9_screenshot_3](https://github.com/surhh/nfitsview/assets/109148999/d007fd4f-a670-41c2-9945-43c598f0e70c)

![nfitsview2_9_screenshot_4](https://github.com/surhh/nfitsview/assets/109148999/57de7b91-4b57-4808-9f5b-5ea4ac179742)

![nfitsview2_9_screenshot_5](https://github.com/surhh/nfitsview/assets/109148999/dd36a34f-3468-4201-8547-410ccdb30be2)

![nfitsview2_9_screenshot_6](https://github.com/surhh/nfitsview/assets/109148999/0328e7ec-4925-4364-8c34-feab5ff115ec)

# About FITS format

The details about FITS format and standards can be found here:

[FITS docs](https://fits.gsfc.nasa.gov/fits_documentation.html)

[FITS standard](https://fits.gsfc.nasa.gov/fits_standard.html)

