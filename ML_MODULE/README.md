# ORGANIZATION
If either A3C or SAQN implementations must be changed, then it is necessary to get the newly generated .c and .h files and uptade the src/ and include/ folders in this directory.

For changing the ML algorithm used:
	1. Define the flag SAQN_RUN or A3C_RUN on src/ml_module.c (ex. #define A3C_RUN)
	2. Re-compile the library (see below) 


# COMPILING
For compiling, run:

	$ cd build/
	$ cmake ..
	$ make install	
