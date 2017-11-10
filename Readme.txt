OPENCL BANANZA:

The executable for this program can be found in Debug/OpenCL.exe

It generates an array of numbers defined in OpenCL.cpp (currently set to 1,048,576). The numbers in the array range from 0 - 32,768).

The numbers are then fed to a kernel called "prime_number_checker.cl" where it determines which and how many of the numbers are prime.

The output shows the speed at which this is done serially (through a prime number solving function (CheckIfPrime())), followed by OpenCL on the CPU, then the GPU, then both.