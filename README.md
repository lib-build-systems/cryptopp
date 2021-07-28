# lib-build-systems
### Mission
To provide a collection of flexible build system files for popular libraries.

### Why
1. Flexibility: users should have more control over how and where library output is created.
2. Seperation of responsibility: build systems shouldn't be a part of a library, but a sibling to a library, like meta data.
3. Standardization: build systems provide too many options, which isn't always a good thing.

### How
Each branch in a repository defines a specific build system for a specific version of the repository's library. This way, version-specific bugfixes or other improvements can be made without influencing other build system files of the library.

### Want to help?
Yes please! I already have my hands full on creating a consistent cross-platform CMake experience for the libraries already included. If you have improvements or ready-and-tested config files for other build systems, don't hesitate to create pull requests per build system, per version.

# openal-soft
Added CMakeLists.txt file for cryptopp version 8.6.0
* Default installation paths:
  * <CMAKE_INSTALL_PREFIX>/include/cryptopp (.h, .hpp)
  * <CMAKE_INSTALL_PREFIX>/share/man (.1, .3, .5)
  * <CMAKE_INSTALL_PREFIX>/bin (.exe, .dll)
  * <CMAKE_INSTALL_PREFIX>/lib (.so, .lib)
  * <CMAKE_INSTALL_PREFIX>/lib/cmake/cryptopp (.cmake, .pc) 
  
