# icecat-win64

This is my first attempt at building a Windows binary of GNU IceCat.
Please see https://www.gnu.org/software/gnuzilla for more information.

I began with instructions from Mozilla for setting up a build environment:
https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Build_Instructions/Windows_Prerequisites

Then created my own .mozconfig, downloaded the latest source from a GNU mirror, ran "mach build" then "mach build installer". The result is the unsigned 7zfx installer checked in here. So far this build is only for 64-bit versions of Windows. I will look up how to PGP sign packages when I have more time.
