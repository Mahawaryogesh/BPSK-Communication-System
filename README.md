# BPSK Communication System

MATLAB simulation of a Binary Phase Shift Keying (BPSK) communication system over an Additive White Gaussian Noise (AWGN) channel.

## Objective

The objective of this project is to simulate a basic digital communication system using BPSK modulation and analyze its performance in the presence of noise.

## System Flow

Random Binary Data
        ↓
BPSK Modulation
        ↓
AWGN Channel
        ↓
BPSK Demodulation
        ↓
BER Calculation

## Implementation

The project generates random binary data and converts the bits into BPSK symbols using:

```matlab
bpsk_signal = 2*bits - 1;
