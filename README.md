# dealii-brew

deal.II source based installer for linux systems based on linuxbrew.

Note: this is an experiment and not ready for consumption!

Goals:
- support major 64bit linux machines (stable/unstable ubuntu at least)
- no sudo required
- minimal requirements (but something like g++ is there)
- use system MPI if available, compile MPI if not
- use system blas if available, use own if not
- fairly complete list of deal.II dependencies (some optional)


Getting started:

source env.sh
brew tap tjhei/dealiisuite
brew install mpich2  # if you don't have mpi
brew install openblas  # if you don't have blas
brew install petsc
brew install dealii



TODO list:
- minimal debian, ubuntu 12.04|14.04|15.04
- with system openmpi, system mpich, no mpi
- blas: system or openblas
- clang, g++, intel
- cluster: palmetto, stampede, ...
- all dependencies
