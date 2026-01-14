# LLM-Optimization

Benchmarking and evaluation of optimization techniques for efficient transformer inference using PyTorch and Hugging Face.

## Overview

This repository contains reproducible experiments and benchmarking code to evaluate trade-offs between accuracy, latency, memory usage, and model size when applying optimization techniques to transformer-based language models.

The project focuses on practical methods for improving inference efficiency on resource-constrained hardware, including:

- Parameter-efficient fine-tuning (LoRA)
- Post-training INT8 quantization
- Unstructured weight pruning

---

## Features

- Experiment pipelines for training and evaluation using PyTorch and Hugging Face Transformers  
- Benchmark scripts to measure inference latency, throughput, and GPU/CPU memory usage  
- Comparative evaluation of different optimization strategies  
- Configurable setups for extending experiments to new datasets or models  

---

## Getting Started

### Requirements

It is recommended to use a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate
