Source code for complete project

This is how to compile the ECGAnalysis software from EP Limited 

1. Download GCC and see that it´s up to date
2. Download make to make the compilation
3. https://archive.physionet.org/physiotools/wfdb-linux-quick-start.shtml 
  a. Follow the instructions here and install WFDB
  

IMPORTANT: You have chosen to build a dynamic (shared) WFDB library in
a directory, /usr/local/lib, that is not normally searched for such
libraries.  In order to use the applications that will be compiled
with this library, it may be necessary to add this directory to your
LD_LIBRARY_PATH.  If your shell is csh or a variant, do this by
typing:
  setenv LD_LIBRARY_PATH /usr/local/lib
Otherwise, do this by typing:
  LD_LIBRARY_PATH=/usr/local/lib
  export LD_LIBRARY_PATH
