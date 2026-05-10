# Security And Privacy

## Local-First Prototype

Look2Act is currently a local-first Windows desktop prototype. The demonstrated functions do not require network access.

For the demonstrated workflow:

- Webcam frames are processed locally.
- Camera frames are not uploaded.
- Calibration logs are not uploaded.
- Configuration files are not uploaded.
- Calibration and configuration are stored locally.
- Reviewers may block network access without affecting the core demo.

## Camera And Calibration Data

The demonstration workflow uses webcam frames for face / landmark detection and eye crop generation. These frames are sensitive because they may contain a user's face or eye-region imagery.

Public screenshots must not include recognizable faces, raw participant images, private desktop content, local paths, or participant-identifying information.

## Dataset Privacy Boundary

The full dataset is not public in this initial artifact repository because it contains real users' eye-region images and session/device metadata. This repository provides anonymized schemas and synthetic examples instead.

## Future Executable Package

Any later Windows demonstration package will include:

- Release notes.
- Third-party notices and license files.
- SHA256 checksum.
- Clear statement of included and excluded resources.

The current initial submission does not include a Windows executable package.
