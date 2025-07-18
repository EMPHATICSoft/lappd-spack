This repository provides the necessary recipe to build otsdaq-acc (LAPPD electronics) with spack.

Instructions:
- Make a spack otsdaq installation
- cd spack-repos
- Clone this repo
- spack repo add lappd-spack
- spack add otsdaq-acc@master%gcc@13.1.0
- spack concretize -f
- spack install

Notes:
- Currently only emphatic-daq05 has all the required dependencies to build with spack installed
- To make otsdaq installation:
  -  Downlowad quick start script from https://github.com/art-daq/otsdaq-demo/blob/develop/tools/ots-quick-spack-start.sh
  - ./ots-quick-spack-start.sh
- Master version of otsdaq-acc compatible with otsdaq v03_02_00  
