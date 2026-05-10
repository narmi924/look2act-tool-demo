# Demonstration Workflow

The Look2Act screencast is designed as a 3-5 minute walkthrough of the Windows desktop prototype and this non-code demonstration artifact repository.

```mermaid
%%{init: {"theme": "base", "themeVariables": {"fontFamily": "Arial, sans-serif", "primaryColor": "#FFFFFF", "primaryTextColor": "#20242B", "primaryBorderColor": "#3B6E9E", "lineColor": "#5C6675", "tertiaryColor": "#F6F8FB"}}}%%
flowchart TD
    Launch["1. Launch and mode selection<br/>Choose English UI and select Classic or Deep mode."]
    Preview["2. Camera preview<br/>Check webcam view, face detection, and eye crop status."]
    Calib["3. 25-point calibration<br/>Collect target observations and save local calibration."]
    Tracking["4. Real-time gaze tracking<br/>Show FPS, face status, calibration status, and gaze output."]
    Validation["5. Fullscreen validation<br/>Inspect calibrated gaze behavior on the full screen."]
    Dwell["6. 3x3 dwell-based interaction page<br/>Trigger large-target interaction through gaze dwell."]
    Artifact["7. Artifact walkthrough<br/>Review documentation, schemas, sample logs, figures, and release boundary."]

    Launch --> Preview --> Calib --> Tracking --> Validation --> Dwell --> Artifact

    classDef entry fill:#FFFFFF,stroke:#3B6E9E,stroke-width:2px,color:#20242B;
    classDef vision fill:#FFFFFF,stroke:#2F8F8A,stroke-width:2px,color:#20242B;
    classDef mapping fill:#FFFFFF,stroke:#B9903D,stroke-width:2px,color:#20242B;
    classDef backend fill:#FFFFFF,stroke:#7A659E,stroke-width:2px,color:#20242B;
    classDef interaction fill:#FFFFFF,stroke:#3C8D57,stroke-width:2px,color:#20242B;
    classDef docs fill:#FFFFFF,stroke:#5C6675,stroke-width:2px,color:#20242B;

    class Launch entry;
    class Preview vision;
    class Calib mapping;
    class Tracking backend;
    class Validation,Dwell interaction;
    class Artifact docs;
```

## Workflow Stages

| Stage | Demonstrated behavior | Review focus |
| --- | --- | --- |
| Launch and mode selection | The Windows desktop tool starts with English UI and Classic / Deep mode selection. | Confirms the explicit mode boundary and Windows desktop setting. |
| Camera preview | The tool displays webcam preview and detection status. | Shows camera readiness, face / landmark detection, and eye crop checking. |
| 25-point calibration | The tool collects calibration observations in a 5x5 target layout and stores calibration locally. | Shows the main demonstration calibration setting. |
| Real-time gaze tracking | The tool reports runtime status such as FPS, face status, calibration status, smoothing, and gaze output. | Shows the calibrated gaze visualization workflow. |
| Fullscreen validation | The tool displays calibrated gaze behavior in a fullscreen validation view. | Shows qualitative tracking behavior for gaze visualization. |
| 3x3 dwell-based interaction page | The tool triggers large-target interaction through gaze dwell. | Shows the end-to-end gaze-driven interaction path. |
| Artifact walkthrough | The screencast presents repository contents, sample schemas, sample logs, figures, and release boundary notes. | Shows what is included and intentionally excluded from the initial artifact. |

## Demonstration Boundary

The demonstration is intended for gaze visualization, large-target selection, and low-cost gaze interaction prototyping. It does not claim mouse-level precision, state-of-the-art accuracy, or replacement of infrared eye trackers.
