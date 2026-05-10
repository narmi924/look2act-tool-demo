# Review Guide

This repository is the public non-code demonstration artifact for the Internetware 2026 Tool Demonstration submission of Look2Act. It helps reviewers inspect the tool concept, demonstration workflow, privacy boundary, model/data availability boundary, media materials, and release boundary.

## Evaluation Scope

The artifact supports review through documentation, screencast material, screenshots, anonymized schemas, synthetic sample logs, and aggregate figures. It does not support source-level reproduction because source code, model weights, ONNX files, `.pth` files, the full dataset, raw participant images, and executable binaries are outside the initial submission boundary.

## Reviewer-Visible Materials

| Material | Location |
| --- | --- |
| Tool overview and runtime pipeline | [README.md](README.md) |
| Project summary | [PROJECT_SUMMARY.md](PROJECT_SUMMARY.md) |
| Demonstration workflow | [DEMONSTRATION_WORKFLOW.md](DEMONSTRATION_WORKFLOW.md) |
| Security and privacy boundary | [SECURITY_AND_PRIVACY.md](SECURITY_AND_PRIVACY.md) |
| Model and data availability | [MODEL_AND_DATA_AVAILABILITY.md](MODEL_AND_DATA_AVAILABILITY.md) |
| Media and materials | [MEDIA_AND_MATERIALS.md](MEDIA_AND_MATERIALS.md) |
| Anonymized schemas | [sample_schema/](sample_schema/) |
| Synthetic sample logs | [sample_logs/](sample_logs/) |
| Aggregate figures | [figures/](figures/) |
| Limitations | [LIMITATIONS.md](LIMITATIONS.md) |
| Release boundary | [RELEASE_BOUNDARY.md](RELEASE_BOUNDARY.md) |

## Review Method

Reviewers can inspect the artifact by reading the workflow description, watching the screencast, examining the English screenshots, and checking the anonymized schemas and sample logs. This review path shows what Look2Act demonstrates and what is intentionally excluded from the initial artifact.

The central demonstration path is:

- Launch and mode selection.
- Camera preview and face / eye crop checking.
- 25-point calibration.
- Real-time gaze tracking.
- Fullscreen validation.
- 3x3 dwell-based interaction page.
- Artifact repository walkthrough.

## Sample Schema And Logs

The files under `sample_schema/` and `sample_logs/` are illustrative and privacy-preserving. They are not extracted participant records. They communicate expected field structure, status-report shape, and evaluation-summary shape without releasing raw eye images, full datasets, or model resources.

## Windows Demonstration Package

A Windows demonstration package is not included in the initial submission artifact. A Windows demonstration package is planned for the camera-ready artifact after release-boundary and third-party license review.

## Known Limitations

See [LIMITATIONS.md](LIMITATIONS.md). The main boundaries are Windows-only support, webcam sensitivity to lighting and head pose, 25-point calibration burden, and the absence of source code, full dataset, model weights, and executable binaries in this initial artifact repository.
