MinGW-w64 Build Scripts

These build scripts are based on Zeranoe's MinGW-w64 build scripts (http://ffmpeg.zeranoe.com/blog/?cat=4)

Differences to Zeranoe's Script v3.2.3:
- New option to build for target OS
- GCC 4.8.1, GMP 5.1.2

Usage:
- Build a Cross-Compiler Toolchain with the script
- Add the resulting binaries into PATH
- Run the script again with the --target-build parameter

---------------------------------------------------------
Version History:
r6 - 2013-06-01
    GCC 4.8.1, GMP 5.12
r5 - 2013-04-13
    Updated to Zeranoe's Script v3.2.3
r4 - 2013-03-24
    Updated to Zeranoe's Script v3.1.0
    Restored winpthreads, threading library can now be choosen on the commandline
    Support for GCC 4.8.0
    Updated to mpfr 3.1.2, binutils 2.23.1
    Updated to gmp 5.1.1, isl 0.11.1 and cloog 0.18.0 when building GCC 4.8.0
r3 - 2012-11-04
    Removed winpthreads build
    Updated mpc to 1.0
r2 - 2012-10-27
    Re-created script based on Zeranoe's Script v3.0.6
    Replaced second script with parameter to the first
r1 - 2012-06-23
    Initial Version
