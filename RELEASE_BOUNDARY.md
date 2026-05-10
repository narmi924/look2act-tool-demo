# Release Boundary

## Initial Submission Artifact

The initial submission artifact consists of:

- Paper.
- Non-code artifact repository.
- Screencast material.
- English screenshots.
- Anonymized schemas.
- Synthetic sample logs.
- Aggregate figures.
- Release and availability documentation.

Source code, the full dataset, model weights, ONNX files, `.pth` files, executable binaries, and raw participant images are not released in this initial artifact repository.

## Data And Model Boundary

The full dataset is not public because it contains real users' eye-region images and session/device metadata. Standalone model weights are not public in the initial submission artifact. The repository provides anonymized schemas and synthetic sample logs to communicate data structure without releasing privacy-sensitive records.

## Windows Demonstration Package

A Windows demonstration package is not included in the initial submission artifact.

A Windows demonstration package is planned for the camera-ready artifact after release-boundary and third-party license review. Any Windows demonstration package released later will include release notes, applicable third-party notices, and a SHA256 checksum.

## Longer-Term Release Direction

Longer-term release work may include a license-clean Windows demonstration package, GUI dependency migration for clearer redistribution, and a more reproducible replay package based on privacy-preserving examples.
