# Dynamics Analysis

This folder contains the code to analyze the dynamics of a CUBA LIF Neuron and choose appropriate values for each use case.

## Objective
Find the proper parameters for the neuron models such that a neuron spikes under the specified conditions.

## Tunable Parameters
- `du`: The current decay rate of a CUBA LIF Neuron
- `dv`: The voltage decay rate of a CUBA LIF Neuron
- `spike_weight`: The weight of a spike, i.e., the current injected into the neuron when receiving a spike.