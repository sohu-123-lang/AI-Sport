# Conditional Gating–Based Cross-Fusion Network for Pre-Stroke Drop Point Prediction 

## Demo Video
![Demo GIF](./TrackNetV2_together3-3-good3.gif)

[Download Video](TrackNetV2_together3-3-good3.mp4) (Right-click → Save As)


## Project Overview

This repository implementation of work "A Conditional Gating–Based Cross-Fusion Network for Pre-Stroke Drop Point
Prediction in Badminton". The demo video above (continuously looping) shows a sample input-output comparison.

## Key Features

- Real-time badminton trajectory prediction
- MonoTrack-based feature extraction
- Visualized pre-stroke drop prediction
- Lightweight test implementation (`test.py`)

## Algorithm Workflow

1. **Feature Extraction**:
   - Process video data through MonoTrack
   - Generated features stored in `PrecessedResultFromTrackNetv2/`

2. **Model Training**:
   - Execute root directory Python scripts
   - Produces `.pt` result files (X1-X4) in `AI-Sport/`

3. **Prediction & Visualization**:
   - Run `test5.py` for sample predictions
   - Final output visualized as shown in the demo video

