# NerfStudioDocker
A Dockerfile to build a CUDA accelerated image with all the fixins


## Changes from main repo:
- Changed the runtime image from "runtime" to "devel" because some nerf methods require nvcc and cuda development tools
- Added ninja-build package to the runtime image because some of the non-standard nerf methods require it
- Designed to run on my RTX 4090 laptop (cuda architecture: 89)
