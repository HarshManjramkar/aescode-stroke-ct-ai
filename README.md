# AesCode Stroke CT AI

Public code repository for the `AI-Based Brain Stroke Detection and Lesion Segmentation from CT Scans` hackathon project.

## Project Goal

Build a two-stage system that:

1. classifies a brain CT scan as `Normal` or `Stroke`
2. localizes hemorrhage regions with a lesion mask
3. presents results through a simple demo interface

## Repository Policy

- This repository is for code, planning, and documentation only.
- Organizer-provided datasets are **not** stored in this public repository.
- Model checkpoints and large artifacts should be kept in private Google Drive or other private storage.

## Working Setup

- Code: GitHub
- Training: Google Colab T4
- Data and checkpoints: Google Drive

## Team Split

- Classification owner: trains and evaluates the stroke classifier
- Segmentation owner: trains and evaluates the lesion segmentation model
- Shared: integration, report, slides, and demo

## Current Status

Planning and project governance are in place. Implementation will follow the BMAD and Ruflo workflow defined in [AGENTS.md](./AGENTS.md).
