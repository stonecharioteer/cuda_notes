================
Lessons on CUDA
================

CUDA is NVIDIA's parallel computing platform and programming model, meant for
general purpose computing on GPUs. CUDA is primarily a C/C++ library, meant to be
used in a way that utilizes the processing capabilities of an NVIDIA GPU.

In a CUDA program, the seqential part of the workload runs on the CPU, which is optimized for
single threaded performance. The compute-intensive portion of the application runs on the thousands
of cores of the GPU in parallel.

NVIDIA's CUDA libraries are available for C, C++, FORTRAN and Python.

Before proceeding, make sure to go through the Setup portion of these notes 
so that you have the runtime libraries properly configured.


