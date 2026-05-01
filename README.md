# Kuramoto-Oscillator
Simulation of the Kuramoto model to study how synchronization emerges in coupled oscillators. Explores phase evolution, order parameter dynamics, and the effect of coupling strength and frequency disorder, demonstrating the transition from incoherence to collective behavior.
# Kuramoto Oscillator Synchronization Model

## Overview
This project simulates synchronization dynamics in a network of coupled oscillators using the Kuramoto model. It demonstrates how individual oscillators with different natural frequencies evolve toward collective phase alignment.

## Model Description
- 100 coupled oscillators with random initial phases  
- Natural frequencies drawn from a normal distribution  
- Global coupling between all oscillators  
- Numerical integration using discrete time steps  

## Key Results
- Oscillators start with random phases  
- Increasing coupling strength leads to phase alignment  
- Order parameter (r) increases toward 1, indicating synchronization  

## Interpretation
The model demonstrates emergent synchronization in a coupled system. As coupling strength increases, individual differences in natural frequency are overcome, resulting in coherent collective behavior.

## How to Run
```bash
pip install numpy matplotlib
python kuramoto_model.py
