MinGW-w64 Build Scripts

These build scripts are based on Zeranoe's MinGW-w64 build scripts (http://ffmpeg.zeranoe.com/blog/?cat=4)

Differences to Zeranoe's Script v3.0.6:
- Updated to GCC 4.7.2, binutils 2.23
- New option to build for target OS

Usage:
- Build a Cross-Compiler Toolchain with the script
- Add the resulting binaries into PATH 
- Run the script again with the --target-build parameter

---------------------------------------------------------
Version History:
r3 - 2012-11-04
    Removed winpthreads build
    Updated mpc to 1.0
r2 - 2012-10-27
    Re-created script based on Zeranoe's Script v3.0.6
    Replaced second script with parameter to the first
r1 - 2012-06-23
    Initial Version