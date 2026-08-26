# CameraX Photo Video Analysis Lab

Reimplementation-oriented Android lab showing **CameraX 1.6.1** preview, JPEG capture, MP4 recording and real-time image analysis in one small project.

## What it demonstrates
- `PreviewView` + lifecycle-bound CameraX use cases.
- `ImageCapture` into `MediaStore`.
- `VideoCapture<Recorder>` with optional microphone audio.
- `ImageAnalysis` with `KEEP_ONLY_LATEST`; the demo computes average Y-plane luminance.
- Runtime permission handling and graceful camera absence.

Requires a camera-capable device/emulator. Video encoders and camera combinations vary by device. Reimplemented as an educational lab; it is not a copy of an upstream sample.
