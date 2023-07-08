# Default distro python 3.8
FROM nvidia/cuda:11.8.0-cudnn8-devel-ubuntu20.04

# We need unzip for vault devcontainer feature (download and unzip)
# We need g++ for torch dynamo (cpp)
RUN apt update && apt install -y unzip g++
