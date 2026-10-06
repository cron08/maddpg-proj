# Multi-Agent Reinforcement Learning with MADDPG

## About

This repository contains code and supporting materials for a pre-publication research project on multi-agent reinforcement learning (MARL), extending the Multi-Agent Deep Deterministic Policy Gradient (MADDPG) framework introduced by Lowe et al.

The project investigates two extensions to MADDPG:

- **Pre-Trained Action Inference (PTAI):** augments each agent’s policy with inferred previous joint actions derived from consecutive observations, providing additional temporal context for decentralized decision-making.
- **Geometric recency-biased experience replay:** samples more heavily from recent transitions in the replay buffer, with the aim of improving learning under the non-stationarity created by simultaneously updating agents.

The methods were implemented in PyTorch and evaluated on competitive environments from the PettingZoo Multi-Agent Particle Environment suite, including Predator–Prey.

## Paper

For the clearest description of the methodology, experiments, and results, see [`paper.pdf`](paper.pdf).

The repository contains experimental code from different stages of the project and is not currently structured as a standalone software package.

## Background

This work builds on the original MADDPG framework introduced by Ryan Lowe, Yi Wu, Aviv Tamar, Jean Harb, Pieter Abbeel, and Igor Mordatch, with affiliations including OpenAI, UC Berkeley, and McGill University.


