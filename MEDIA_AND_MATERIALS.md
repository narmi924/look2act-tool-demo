# Media And Materials

This document summarizes the non-code media, figures, schemas, and logs included in the Look2Act demonstration artifact.

## Screencast

The demonstration video is currently being prepared, and the link will be updated soon.

The video will present the Windows demonstration workflow and the artifact repository scope.

## Screenshots

The `screenshots/` directory contains English screenshots of the demonstrated Windows workflow.

| Filename | Demonstrated view |
| --- | --- |
| `01_mode_language_selection.png` | Launch dialog with English UI and Classic / Deep mode selection. |
| `02_home_page.png` | Main home page. |
| `03_camera_preview_anonymized.png` | Camera preview and detection-status view using anonymized/safe content. |
| `04_eye_crop_examples.png` | Eye crop status/examples. |
| `05_25_point_calibration.png` | 25-point calibration view. |
| `06_realtime_tracking_and_validation.png` | Real-time tracking and fullscreen validation view. |
| `07_3x3_dwell_interaction.png` | 3x3 dwell-based interaction page. |
| `08_gomoku_interaction.png` | Gaze-driven Gomoku interaction view. |
| `09_settings_page.png` | Settings page. |

Screenshots in the public artifact do not contain raw participant images, private paths, personal desktop content, or participant-identifying information.

## Figures

| Filename | Description |
| --- | --- |
| `fig_dataset_split_en.png` | Aggregate dataset split summary. |
| `fig_fixed_test_angle_error_en.png` | Fixed-test angular error distribution. |
| `fig_loo_angle_error_en.png` | 31-user leave-one-user-out angular error with anonymized labels. |
| `fig_loo_screen_error_en.png` | 31-user leave-one-user-out screen-space error with anonymized labels. |
| `fig_calibration_strategy_en.png` | Aggregate calibration strategy comparison. |
| `look2act_pipeline_en.mmd` | Mermaid source for the runtime pipeline diagram embedded in `README.md`. |
| `look2act_demo_workflow_en.mmd` | Mermaid source for the demonstration workflow diagram embedded in `DEMONSTRATION_WORKFLOW.md`. |

## Schemas And Sample Logs

| Material | Location |
| --- | --- |
| Anonymized label schema | [sample_schema/labels_schema.csv](sample_schema/labels_schema.csv) |
| Anonymized metadata schema | [sample_schema/meta_schema.json](sample_schema/meta_schema.json) |
| Synthetic calibration log example | [sample_schema/calibration_log_example.json](sample_schema/calibration_log_example.json) |
| Synthetic runtime status example | [sample_logs/runtime_status_example.json](sample_logs/runtime_status_example.json) |
| Aggregate evaluation summary example | [sample_logs/evaluation_summary_example.md](sample_logs/evaluation_summary_example.md) |

## Future Package Materials

The initial submission artifact does not include a Windows executable package. A Windows demonstration package is planned for the camera-ready artifact after release-boundary and third-party license review.
