# FPGA-Based-CNN-Accelerator-for-Handwritten-Digit-Recognition-ONGOING-
Designed an FPGA-based accelerator for handwritten digit recognition using the LeNet-5 CNN architecture. Implemented CNN processing modules in Verilog HDL and interfaced a Raspberry Pi Pico through SPI communication.

# FPGA-Based CNN Accelerator for Handwritten Digit Recognition

## Overview
This project focuses on accelerating CNN inference for handwritten digit recognition using an Intel Cyclone IV FPGA.

The system uses a quantized LeNet-style neural network trained on the MNIST dataset.

## Objectives
- Implement CNN acceleration on FPGA
- Reduce computational latency
- Demonstrate hardware-software co-design

## Hardware
- Intel Cyclone IV FPGA
- Raspberry Pi Pico (RP2040)

## Software Tools
- Quartus Prime
- Python
- Verilog HDL

## CNN Architecture
- Convolution Layer 1
- ReLU Activation
- Max Pooling
- Convolution Layer 2
- Fully Connected Layer
- Softmax Output

## Technologies
- FPGA Design
- Verilog HDL
- Machine Learning
- Embedded Systems

## Results
Successfully designed and simulated CNN accelerator modules for digit classification.

## Future Scope
- Complete FPGA deployment
- Hardware optimization
- Support larger neural networks
