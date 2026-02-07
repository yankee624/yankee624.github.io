---
layout: page
title: Orchestra
description: DNN Inference Framework for Heterogeneous Processors on Mobile SoC
importance: 1
category: research
date: Jan. 2025 ~ Present
---

## Orchestra: DNN Inference Framework for Heterogeneous Processors on Mobile SoC

An ongoing research project focused on building an efficient deep learning inference framework for heterogeneous processors on mobile systems-on-chip (SoC).

### Key Features

- **MLIR-based Compilation Framework**: Designing and implementing a compiler infrastructure using Multi-Level Intermediate Representation (MLIR) for DNN inference on heterogeneous processors
- **Efficient Runtime System**: Building a high-performance runtime with zero-copy memory sharing capabilities
- **Flexible Operator Assignment**: Enabling dynamic task assignment across different processing units (CPU, GPU, NPU)
- **Task Migration Support**: Supporting seamless migration of compute tasks between heterogeneous processors

### Technical Approach

The project leverages MLIR's compiler infrastructure to generate optimized code for different hardware backends while maintaining a unified programming model. The runtime system implements zero-copy memory sharing to minimize data movement overhead and enable efficient collaboration between heterogeneous processors.

### Status

Active development (January 2025 ~ Present)
