# TinyML: CIFAR-10_Image_Detection_nrf7002DK
Deployed CIFAR-10-based Object Detection/ Classification model on Nordic nrf7002DK_nrf5340

# CIFAR-10 Image Detection on nRF7002DK

## Introduction
This project demonstrates the implementation and deployment of a CIFAR-10-based image classification model on the nRF7002DK development kit. The purpose of this project is to showcase the ability to run a convolutional neural network for image classification directly on an embedded device, using TensorFlow Lite Micro. The model classifies images into one of the CIFAR-10 dataset categories, specifically demonstrating a sample image of a ship.

## Project Setup

### Prerequisites
- TensorFlow Lite Micro
- nRF Connect SDK
- ARM GCC Compiler
- CMake
- A physical nRF7002DK development kit

### Installation and Configuration
1. **Clone the repository:** 
https://github.com/gowtham323/CIFAR-10_Object_Detection_nrf7002DK.git 
2. **Navigate to the project directory:**
   cd CIFAR-10-Object-Detection-nRF7002DK
3. **Set up the nRF Connect SDK environment** according to the official nRF Connect SDK instructions available [here](https://developer.nordicsemi.com/nRF_Connect_SDK/doc/latest/nrf/gs_installing.html).

### Building the Project
1. **Set up your build environment:**
   Install nrf Connect SDK for VSCode, latest nrf toolchain, C/C++, Python.
2. **Build the project:**
   use the build option available on nrf menu (you can find it in side panel after installing the nrf extension pack)
## Running the Project
- Connect your nRF7002DK to your PC using a USB cable.
- Flash the built firmware onto the nRF7002DK using the flash available on the nrf connect menu.
