# gsl-mkl
CMake build of GNU Scientific Library (GSL) with Intel Math Kernel Library (MKL) cblas support

The base of the cmake gsl implementation is from https://github.com/ampl/gsl
FindMKL should be downloaded from https://github.com/openmeeg/findmkl_cmake/blob/master/cmake/FindMKL.cmake and copied to the project or the cmake share\camke-x.xx\modules directory

# Build
Tested with CMake 3.15.1 and Visual Studio 2017

Run the cmake-gui and set MKL_ROOT_DIR to the path of Intel MKL (Typical for Windows: C:\Program Files (x86)\IntelSWTools\compilers_and_libraries_2019\windows\mkl) and press the Generate button. 


