MinGW-w64 Build Scripts

These build scripts are based on Zeranoe's MinGW-w64 build scripts (http://ffmpeg.zeranoe.com/blog/?cat=4)

Differences to Zeranoe's Script v3.6.7:
- New option to build for target OS
- GCC 6.1, MinGW-w64 4.0.6, binutils 2.25.1, and updates to all dependency libraries

Usage:
- Build a Cross-Compiler Toolchain with the script
- Add the resulting binaries into PATH
- Run the script again with the --target-build parameter

---------------------------------------------------------
Version History:
r17 - 2016-06-14
    GCC 6.1
r16 - 2016-06-14
    GCC 5.4, MinGW-w64 4.0.6, mpfr 3.1.4, isl 0.16.1
r15 - 2015-12-04
    Updated to Zeranoe's Script v3.6.7
    GCC 5.3, gmp 6.1.0, isl 0.15
r14 - 2015-12-01
    binutils 2.25.1, MinGW-w64 4.0.4 (+ patches)
r13 - 2015-07-20
    GCC 5.2
r12 - 2015-07-01
    GCC 5.1
r11 - 2015-06-30
    Updated to Zeranoe's Script v3.6.6
    GCC 4.9.3, MinGW-w64 4.0.2
    mpfr 3.1.3
r10 - 2014-11-10
    GCC 4.9.2, MinGW-w64 3.3.0
r9 - 2014-07-30
    Updated to Zeranoe's Script v3.6.0
    GCC 4.9.1
r8 - 2014-05-22
    Updated to Zeranoe's Script v3.5.8
    GCC 4.8.3
r7 - 2013-10-20
    Updated to Zeranoe's Script v3.5.0
    GCC 4.8.2
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
