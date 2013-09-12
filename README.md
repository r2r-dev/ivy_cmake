This repository contains three source trees
built using CMake generator and ivy/ant as 
binary artifacts dependency manager:

cmake_inccalc: header files needed by __libcalc__ and __calcexe__
cmake_libcalc: shared library and link target for __calcexe__ 
cmake_calcexe: final target

Purpose of above is to present ivy capabilities
in relation to non-java projects

ivy publish and retrieve binary artifacts from Artifactory with default settings.
For details, please check any of ivysettings.xml 
