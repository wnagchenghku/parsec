Typical (and recommended) systems configuration for Parrot (a.k.a., xtern)
================
Hardware: we have tried both 4-core and 24-core machines with 64 bits.
OS: Ubuntu 11.10.
gcc/g++: 4.5 (please use this gcc version if possible). One suggestion
is you could install 4.5 and setup a local link for it in your own PATH environment 
variable, so that your "gcc -v" command would return 4.5.X.




Installing Parrot (xtern)
================

0. Install some libraries/tools.
> sudo apt-get install gcc-4.5 g++-4.5 gcc-multilib g++-multilib


1. Add $XTERN_ROOT (the absolute path of "xtern") into environment variables
in your ~/.bashrc. Run "echo $XTERN_ROOT" and "echo $LD_LIBRARY_PATH"
to make sure they are correct.
> export XTERN_ROOT=the absolute path of "smt+mc/xtern"

