# Project Summary

## Tool Overview

Look2Act is a Windows desktop tool for webcam-based gaze visualization and gaze-driven interaction prototyping. The tool supports two modes:

| Mode | Description |
| --- | --- |
| Classic | Demonstration mode based on classic image-processing features. |
| Deep | Research-oriented mode using the GazeNetV2 gaze backend. |

The main demonstration calibration setting is 25-point calibration. 9-point calibration is treated only as an experimental comparison.

## Dataset And Evaluation Summary

The preliminary evaluation summarized in this artifact uses:

| Item | Value |
| --- | --- |
| Users | 31 |
| Devices | 16 |
| Valid samples | 7,395 |

Preliminary aggregate evaluation numbers:

| Metric | Value |
| --- | --- |
| Fixed test mean angular error | 2.8206 deg |
| 31-user leave-one-user-out mean angular error | 2.4788 deg |
| 31-user leave-one-user-out mean screen-space error | 321.3820 px |

These numbers provide demonstration evidence for the submitted tool. They are not state-of-the-art claims and are not claims of mouse-level precision.

## Platform And Runtime Boundary

Look2Act currently targets Windows desktop. The demonstrated functions do not require network access. Webcam frames are processed locally. Calibration logs and configuration files are stored locally for the demonstrated workflow.

## Initial Artifact Boundary

The initial artifact includes documentation, screencast material, screenshots, anonymized schemas, synthetic sample logs, and aggregate figures. It does not include source code, the full dataset, raw participant images, standalone model weights, ONNX files, `.pth` files, or a Windows executable package.
