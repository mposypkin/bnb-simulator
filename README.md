# bnb-simulator
Simulation of parallel implementation of branch and bound method
Build instructions:
1. Clone or download BNB-Solver and put to the same folder as this repository
2. link BNB-Solver to the root folder: from the root folder type 'ln -s ../BNB-solver ."
3. build libjson: from the root folder type 'cd BNB-solver/libjson; make'
4. build simulator: from the root folder 'cd build; cmake CMakeLists.txt; make'

Upon successful build process the executable can be run from the build folder. 
