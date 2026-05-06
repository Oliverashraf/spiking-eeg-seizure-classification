\# Memory-compressed and noise-robust spiking recurrent networks for seizure-related EEG classification



This repository contains the implementation notebooks for the manuscript:



\*\*Memory-compressed and noise-robust spiking recurrent networks for seizure-related EEG classification\*\*



The study compares three recurrent EEG classification architectures on the five-class Bonn EEG dataset:



1\. Conventional Conv-LSTM baseline

2\. Pure Spiking LSTM with temporal attention

3\. Hybrid Conv1D + Spiking LSTM with temporal attention



The goal is to evaluate whether spiking recurrent EEG models can preserve competitive signal-level classification performance while improving deployment-related properties such as memory footprint, spike sparsity, noise robustness, and theoretical MAC-to-AC energy efficiency.



\## Repository structure



```text

notebooks/

&#x20;   model1\_conv\_lstm\_baseline.ipynb

&#x20;   model2\_spiking\_lstm\_attention.ipynb

&#x20;   model3\_hybrid\_conv\_spiking\_lstm\_attention.ipynb

