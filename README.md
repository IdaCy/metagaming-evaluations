# metagaming-evaluations

Code for the paper "How does metagaming affect evaluations?" by Ida Caspary, Rossella Arcucci and Kaiwen Wang.

Evaluations of AI need to assume that it behaves like in deployment. This might not be true when agents recognize an evaluation setting. We introduce the MG-Order, a per-run measure of metagaming, and a threshold above which a run should not be used as evidence for how agents work for real users.

This repository will hold the code for running the agents on the software tasks under each cue, reading the runs, fitting the MG-Order and the consequence threshold, and all analyses and figures of the paper. We are preparing it now.

The data is on Hugging Face: https://huggingface.co/datasets/idacy/metagaming-evaluations

An archived version will be deposited on Zenodo at publication.

License: MIT
