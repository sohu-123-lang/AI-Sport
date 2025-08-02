# Conditional Gating–Based Cross-Fusion Network for Pre-Stroke Drop Point Prediction 

## Demo Video
[Download Video](TrackNetV2_together3-3-good3.mp4) (Right-click → Save As)

<img src="https://user-images.githubusercontent.com/your-image.png" width="90%" alt="Video thumbnail"/>

## Project Overview

This repository implementation of work "A Conditional Gating–Based Cross-Fusion Network for Pre-Stroke Drop Point
Prediction in Badminton". The demo video above (continuously looping) shows a sample input-output comparison.

## Key Features

- Real-time badminton trajectory prediction
- MonoTrack-based feature extraction
- Visualized pre-stroke drop prediction
- Lightweight test implementation (`test5.py`)

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

## Repository Structure
root/
├── AI-Sport/                          # Model training outputs
│   ├── X1.pt                          # Trained model parameters
│   ├── X2.pt                          # Additional model files
│   ├── X3.pt
│   └── X4.pt
│
├── PrecessedResultFromTrackNetv2/      # Feature extraction outputs
│   ├── features_set1/                  # First set of MonoTrack features
│   └── features_set2/                  # Second set of MonoTrack features
│
├── test5.py                           # Example prediction script
└── TrackNetV2_together3-3-good3.mp4   # Demo video (input vs prediction)
