# AEP Research Paper 001: Deterministic Adjudication Lattices and Evolutionary Convergence in Constrained Generative Agent Populations

Research paper for the Agent Element Protocol (AEP) by the New Lisbon Agency/Iberian Peninsula Human Civilization Continuation Project (IPHCCP).

## Files

- DAL-AEP-research-paper.pdf - Full paper
- DAL-AEP-research-paper.pdf.ots - OpenTimestamps proof of prior existence

## Verify timestamp

Install OpenTimestamps (https://opentimestamps.org/) and run:

    ots verify DAL-AEP-research-paper.pdf.ots

This confirms the document existed at the stamped date via Bitcoin blockchain attestation.

## Important Notice

Keep in mind: this first research paper has not included the option intended for AEP v2.0 to simply add memory to the Deterministic Adjudication Lattices.

With memory-augmented lattices: 
This changes the calculus significantly. If the lattice retains memory of previously validated outputs and their structure, it can effectively raise α_T for any model feeding into it - the lattice's memory provides implicit conditioning that the paper's Theorem 3.2 only gets via in-context exemplars (with all the fragility Observation 3.2 admits). 

A memory-augmented lattice could make α_T for a cheap model approach α_T for a frontier model, because the lattice itself is doing the heavy lifting of constraining the output space.
