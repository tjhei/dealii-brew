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