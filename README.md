#Vortex Engine#

Experimental Ultrasound Signal Processing and Feature Representation
Overview

Vortex Engine is an experimental research project exploring alternative approaches to processing and representing raw ultrasound data for feature analysis.
The project investigates whether computational processing approaches can produce a more spatially concentrated representation of selected signal features when compared with a baseline peak-detection approach applied to B-mode ultrasound data.

⚠️ Research Status: Vortex Engine is an experimental research project. Its results do not currently establish clinical accuracy, diagnostic superiority, or improved medical outcomes. Further validation and quantitative evaluation are required.


RESEARCH OBJECTIVE 

The objective of this project is to explore alternative computational approaches for transforming and analyzing ultrasound signal data and to investigate how these approaches affect the spatial representation of detected features.
The project focuses on:
✓ Processing ultrasound channel/RF data.
✓Constructing a baseline B-mode representation.
✓Applying signal-processing and feature-selection steps.
✓Building a graph-based representation of selected signal features.
✓Producing a Vortex feature/ridge representation.
[Comparing the spatial characteristics of the resulting representation with baseline B-mode peak detection.


Processing Pipeline 

UFF Ultrasound Data
        ↓
Raw Channel Data Extraction
        ↓
Depth Calculation
        ↓
B-mode Reconstruction
        ↓
Time Gain Compensation
        ↓
Ring-Down Region Removal
        ↓
Signal Thresholding
        ↓
Peak Detection
        ↓
Graph-Based Ridge Connection
        ↓
Automatic Ridge Selection
        ↓
Spline Fitting
        ↓
Vortex Feature Representation
        ↓
Comparison with B-mode Peaks


Initial Experimental result 


Dataset
L7_CPWC_TheGB.uff
An initial experimental run produced a Vortex representation that was visually more spatially concentrated than the baseline B-mode peak detections.
The experiment generated quantitative measurements including:
1)Number of detected points
2)Lateral coverage
3)Depth range
4)Depth variation

Current Interpretation

The initial experiment suggests that the Vortex processing pipeline can generate a concentrated representation of selected signal features.

However, spatial concentration alone does not demonstrate improved anatomical detection or diagnostic accuracy. Additional experiments, ground-truth comparisons, and quantitative validation are required.

Current Research Status

The project is currently in an exploratory stage.
Future work includes:
Testing additional ultrasound datasets.
Comparing results across different anatomical structures.
Developing quantitative evaluation metrics.
Comparing outputs against known ground truth where available.
Investigating reproducibility across experiments.
Exploring potential integration of AI-based feature analysis.

 Technologies and Tools
.Python
.NumPy
.SciPy
.Matplotlib
.h5py
.NetworkX
.Jupyter Notebook
.Kaggle
