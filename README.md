# Welcome to nFITSview page!

The latest version (3.8) of nFITSview for Windows 64-bit to download (starting from version 3.6 Windows 10 or later is required):

[nfitsview3_8-setup-x64.exe](https://github.com/surhh/nfitsview/releases/download/v3.8/nfitsview3_8-setup-x64.exe)

The latest version (3.8) of nFITSview for Linux 64-bit (Debian-based) to download: 

[nfitsview3_8-x64.deb](https://github.com/surhh/nfitsview/releases/download/v3.8/nfitsview3_8-x64.deb)

The dependencies for installing in Linux are:

libboost-iostreams1.88.0 (>= 1.88.0), libc6 (>= 2.34), libgcc-s1 (>= 3.0), libpng16-16t64 (>= 1.6.46), 
libqt6charts6 (>= 6.6.1), libqt6core6t64 (>= 6.9.1), libqt6gui6 (>= 6.1.2), libqt6network6 (>= 6.1.2), 
libqt6widgets6 (>= 6.1.2), libstdc++6 (>= 14)

***Experimental (portable) version for macOS***

[nfitsview3_7_portable_mac.zip](https://github.com/surhh/nfitsview/releases/download/v3.7/nfitsview3_7_portable_mac.zip)

# About nFITSview  (next FITS viewer)
nFITSview - A user-friendly FITS image viewer

Currently nFITSview supports the following formats and features:

-    8-bit images
-    16-bit integer images
-    32-bit floating point and integer images
-    64-bit floating point and integer images
-    Exporting image HDUs as PNG/TIFF/JPEG/BMP/PPM files
-    Bulk exporting of all image HDUs as PNG files
-    Percentile and stretching support
-    Image zoom in/out
-    HDU header syntax view
-    Raw data hex preview
-    Both regular and compressed (.fz) FITS files are supported
-    Command line exporting of FITS file  (see -h, -e command line switches)
     
     *Note: the console output is not visible on Windows platform. The command line 
     supports image exporting only in "Original" mapping mode.*
    
# How to build under Linux

The original development of nFITSview is done under Linux, so the easiest and the fastest way to build is under Linux.

- Just build in Qt Creator. 
- It should be also possible to build using CMake from the command line. Run the following cmake commands:

        cmake -DCMAKE_BUILD_TYPE=Release -DCMAKE_CXX_FLAGS_RELEASE="-O3 -DNDEBUG" -B build -S .
  
        cmake --build build

  The nfitsview execuatble will be located in the build directory.

# How to build under Windows

Normally there is no need to build under Windows as the install package is provided. 
Anyway, for building under Windows one would need to download/install/build all the dependencies (boost, zlib, libpng), then fix the
corresponding pathes for the libraries in the CMakeLists.txt file and then build the project using Qt Creator.


# Screenshots

<img width="2050" height="1174" alt="nfitsview3_8_screenshot_3" src="https://github.com/user-attachments/assets/f9558e9e-2f41-47f0-9632-140dc15d05d6" />
<img width="2050" height="1174" alt="nfitsview3_8_screenshot_2" src="https://github.com/user-attachments/assets/a444eca9-1471-458b-8abe-e70a3b939eea" />
<img width="2050" height="1174" alt="nfitsview3_8_screenshot_1" src="https://github.com/user-attachments/assets/73ac1dab-423e-4d16-bf8a-a8c820a13484" />



# About FITS format

The details about FITS format and standards can be found here:

[FITS docs](https://fits.gsfc.nasa.gov/fits_documentation.html)

[FITS standard](https://fits.gsfc.nasa.gov/fits_standard.html)

