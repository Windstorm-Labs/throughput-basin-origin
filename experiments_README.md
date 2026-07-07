# Throughput Basin Origin — Experiment Code & Data

Four orthogonal experiments underlying the paper. Each `exp-N/` directory holds
`code/` (the runnable scripts) and `results/` (the CSV outputs used in the paper's
tables and figures):

- **exp-1** — cross-corpus / self-eval throughput across entropy levels
- **exp-2** — quantization cliff and Pareto analysis
- **exp-3** — seven-corpus BPT comparison, shuffling cascade, energy
- **exp-6** — controlled-entropy energy measurements
- **exp-8** — multimodal (vision/audio) throughput

Reproduce from each script with a standard scientific-Python environment.
