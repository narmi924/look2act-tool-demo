# Model And Data Availability

## Initial Submission Boundary

The initial submission artifact does not publicly release:

- Full dataset.
- Raw eye-region or face images.
- Trained model weights.
- ONNX files.
- `.pth` checkpoint files.
- Source code.
- Windows executable package.

## Dataset Boundary

The full dataset is not public because it contains real users' eye-region images and session/device metadata. Even when participant identifiers are removed, raw eye-region images and device/session metadata can remain sensitive.

This repository therefore provides anonymized schemas and synthetic sample logs instead of participant records.

## Model Boundary

Standalone model weights are not public at this stage. The Deep mode is described as using GazeNetV2, but the trained weights and ONNX files are not included in this initial artifact repository.

## Provided Schema Files

| File | Purpose |
| --- | --- |
| [sample_schema/labels_schema.csv](sample_schema/labels_schema.csv) | Describes expected label fields without real participant rows. |
| [sample_schema/meta_schema.json](sample_schema/meta_schema.json) | Shows an anonymized session metadata structure. |
| [sample_schema/calibration_log_example.json](sample_schema/calibration_log_example.json) | Shows a synthetic calibration log shape using example values only. |

## Provided Sample Logs

| File | Purpose |
| --- | --- |
| [sample_logs/runtime_status_example.json](sample_logs/runtime_status_example.json) | Synthetic runtime status example. |
| [sample_logs/evaluation_summary_example.md](sample_logs/evaluation_summary_example.md) | Preliminary aggregate evaluation summary, not a state-of-the-art claim. |

All sample files are illustrative and privacy-preserving.
