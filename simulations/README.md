# Conscience Architecture — Bandit Simulation

This directory contains the Python simulation that tests the **six falsifiable predictions** of Contextual Resonance using Thompson Sampling.

## The Model
The environment models multiple independent platforms as contextual bandits. Each platform updates its posterior (Beta-Bernoulli) based on the reward signal it receives from the user's authentic behavior.

The script simulates 10,000 steps of engagement across 10 possible arms to demonstrate how independent learners converge on the same high-affinity behavioral signal **without sharing data**.

## How to Run

1. Install dependencies (only needs to be done once):
   ```bash
   pip install -r requirements.txt
