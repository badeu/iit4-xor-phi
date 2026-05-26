# IIT 4.0: Φ Computation for a Canonical XOR Network

A step-by-step Python implementation of the Integrated Information Theory 4.0 
"unfolding" recipe, applied to the canonical three-node XOR benchmark network 
in state (A, B, C) = (0, 0, 0).

## What this notebook does

Using PyPhi on the `feature/iit-4.0` branch, the notebook walks through all six 
steps of the IIT 4.0 unfolding procedure — Existence, Intrinsicality, Information, 
Integration, Exclusion, and Composition — computing the full Φ-structure including 
system integrated information (φ_s), distinctions (φ_d), relations (φ_r), and 
Big Φ = Σφ_d + Σφ_r.

## Motivation

This implementation serves as a ground-truth benchmark for information-theoretic 
measures of emergence and integration, with the longer-term goal of applying 
analogous frameworks to the internal representations of large language models.

## Reference

Albantakis et al., *PLoS Computational Biology* 19(10): e1011465 (2023)  
https://doi.org/10.1371/journal.pcbi.1011465
