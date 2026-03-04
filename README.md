# TM-DRO Beamforming

Learning-Based Robust Beamforming via Covariance Spectra with Token Mixing

## Overview

This repository contains the official implementation of the paper:

**Learning-Based Robust Beamforming via Covariance Spectra with Lightweight Token Mixing**

Adaptive beamforming methods such as MVDR and LCMV are known to suffer severe performance degradation under steering vector mismatch and limited snapshot conditions. Classical robust beamforming approaches typically rely on manually designed uncertainty sets or carefully tuned regularization parameters, which may lead to overly conservative solutions or catastrophic failures in challenging scenarios.

To address this issue, this project proposes a **learning-based robust beamforming framework** that directly learns the mapping from the **sample covariance matrix** to beamforming weights. The proposed method introduces a lightweight **token-mixing mechanism** operating on covariance spectra representations, which enables the network to capture global spectral structures of the covariance matrix while preserving physical interpretability.

Instead of explicitly specifying uncertainty sets, the model implicitly learns robustness through end-to-end optimization of the **output SINR objective** under diverse simulated environments.

Simulation results demonstrate that the proposed method consistently achieves near-optimal performance across a wide range of **SNR levels, snapshot regimes, and steering vector mismatch conditions**, significantly reducing the need for manual parameter tuning required by conventional robust beamforming techniques.

## Repository Structure
