# bnb-simulator
Simulation of parallel implementation of branch and bound method
Build instructions:

1. Clone or download BNB-Solver and put to the same folder as this repository

2. link BNB-Solver to the root folder: from the root folder type 

ln -s ../BNB-solver .

3. build libjson: from the root folder type 

cd BNB-solver/libjson
make

4. prepare folder for building: copy 'build' folder to 'bld':

 cp -r build bld

5. build simulator: from the root folder:

 cd bld
 cmake CMakeLists.txt
 make

6. checking the integrity of the build: from the 'bld' folder run 

./bnbtest

type '10 10' and press Enter. The program should produce a meningful trace. 
