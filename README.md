libdnnl for Unikraft
===================
This is a port of Intel's DNNL to Unikraft. The port has a number of
dependencies. To meet them, ensure that you have the following libs
added to your LIBS variable in your app's Makefile:
						
 * CXX standard library, e.g. `libunwind`, `compiler-rt`, `libcxxabi`,
  `libcxx`
  * `libc`, e.g. `newlib`
  * an intrinsics package, e.g., `intel-intrinsics` or `arm-intrinsics`
  
Please refer to the `README.md` as well as the documentation in the `doc/`
subdirectory of the main unikraft repository.
