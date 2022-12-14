# Welcome to nFITSview page!

The latest version (1.7) of nFITSview for Windows 64-bit to download:

[nfitsview1_7-setup-x64.exe](https://github.com/surhh/nfitsview/releases/download/v1.7/nfitsview1_7-setup-x64.exe)

The latest version (1.7) of nFITSview for Linux 64-bit (Debian-based) to download: 

[nfitsview1_7-x64.deb](https://github.com/surhh/nfitsview/releases/download/v1.7/nfitsview1_7-x64.deb)

The dependencies for installing in Linux are:

libboost-iostreams1.74.0 (>= 1.74.0), libc6 (>= 2.34), libgcc-s1 (>= 3.0), libpng16-16 (>= 1.6.2-1)

libqt5core5a (>= 5.15.1), libqt5gui5 (>= 5.0.2), libqt5gui5-gles (>= 5.0.2), libqt5widgets5 (>= 5.15.1), libstdc++6 (>= 11)

# About nFITSview  (next FITS viewer)
nFITSview - A simple and user-friendly FITS image viewer

Currently nFITSview supports the following formats and features:

-    16-bit integer images
-    32-bit floating point and integer images
-    64-bit floating point and integer images (experimental, may still not work   
     as it should)
-    Exporting image HDUs as PNG/TIFF/JPEG/BMP files
-    Bulk exporting of all image HDUs as PNG files
-    RGB gamma correction, grayscale and "Eye Comfort" filter
-    Image zoom in/out
-    HDU header syntax view
-    Raw data hex preview
-    Only uncompressed FITS data is supported 
-    Command line exporting of FITS file  (see -h, -e command line switches).
     
     *Note: the console output is not visible on Windows platform.*
    
# How to build under Linux

The original development of nFITSview is done under Linux, so the easiest and the fastest way to build is under Linux.

- just build in Qt Creator. 
- it should be also possible to build using CMake from the command line.

# How to build under Windows

Normally there is no need to build under Windows as the install package is provided. 
Anyway, for building under Windows one would need to download/install/build all the dependencies (boost, zlib, libpng), then fix the
corresponding pathes for the libraries in the CMakeLists.txt file and then build the project using Qt Creator.


# Screenshots

![nfitsview1_6_screenshot_1](https://user-images.githubusercontent.com/109148999/208360548-7fcf52cb-2d3c-4ccd-a377-dbf21e601f29.png)
![nfitsview1_6_screenshot_2](https://user-images.githubusercontent.com/109148999/208360553-a52ab2da-9a58-48c3-a12b-c6b7b0934504.png)
![nfitsview1_6_screenshot_3](https://user-images.githubusercontent.com/109148999/208360556-f3f59db8-f518-461c-82cd-2aecf22b9a17.png)
![nfitsview1_6_screenshot_4](https://user-images.githubusercontent.com/109148999/208360557-a89d83f9-e54f-4cf6-8b53-9a123f1ef610.png)

# About FITS format

The details about FITS format and standards can be found here:

[FITS docs](https://fits.gsfc.nasa.gov/fits_documentation.html)

[FITS standard](https://fits.gsfc.nasa.gov/fits_standard.html)

