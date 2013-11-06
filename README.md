Find-Leap
=========

CMake module to find the Leap SDK for Leap Motion's hand tracking device

Platforms
---------

Currently only OSX and Linux. Some stubs for Windows are provided, please feel free to 
fork and finish these.

Use
---

You need to copy a couple of files from the Leap\_SDK folder to your system.

### Mac OS X

Copy `include/Leap.h` to `/usr/local/include/`
then `lib/libLeap.dylib` to `/usr/local/lib/`

### Linux

The .deb package from LeapMotion installs the library but not the
include file.
Copy `include/Leap.h` to `/usr/local/include/`
