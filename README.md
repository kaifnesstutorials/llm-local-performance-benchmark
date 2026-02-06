# llm-local-performance-benchmark
This repository contains a single Jupyter notebook that compares the basic runtime performance of a few locally hosted large language models using Ollama. The goal is to observe how different models behave on a resource-constrained local machine.

Models Tested:

Phi
Mistral
Gemma

Each model is evaluated:
without additional context
with added contextual input

Metrics Collected:

The following metrics are extracted from Ollama responses:
Load duration (seconds)
Prompt processing rate (tokens/sec)
Evaluation / generation rate (tokens/sec)

These metrics focus only on performance, not output quality.

Environment:

Python
Jupyter Notebook
Ollama
Pandas
Matplotlib

All tests were run locally on a personal machine with limited storage and compute.

Output:

Tabular comparison of model metrics
Bar plots for visual comparison of load time and token rates
Example output image is included.

Limitations:

Only a small number of models are tested
Results are hardware-dependent
No accuracy or qualitative evaluation is performed

Notes:

This is a simple experimental notebook, intended for learning and exploration rather than comprehensive benchmarking.
