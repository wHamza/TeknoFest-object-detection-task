# Teknofest Object Detection

An object-detection experiment created for a Teknofest task. The repository includes a YOLO model, a notebook-based inference workflow, and sample image/video outputs.

## What is included

- YOLO inference with Ultralytics
- Frame-by-frame video processing with OpenCV
- Example inputs and rendered detection videos
- A trained checkpoint at `models/ajax.pt`

## Quick start

```bash
pip install ultralytics opencv-python jupyter
jupyter notebook a.ipynb
```

Update the input video path in the notebook before running the inference cells.

## Repository notes

This is an experimental competition prototype. Large model and media files are included for demonstration; production use would benefit from a versioned release or external artifact storage.
