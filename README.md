# Vision-Based Public Transport Flow Analysis & Multi-Agent Simulation

## Overview
This project combines Computer Vision and NetLogo-based Agent-Based Modeling (ABM) to analyze passenger flow and explore demand-aware public transport management.

The Computer Vision component is designed to process **images and videos** to detect and count passengers, while the NetLogo simulation models passengers, buses, and bus stops to study passenger demand and bus allocation strategies.

## Objectives
- Detect and count passengers from images and video footage.
- Analyze passenger flow and estimate demand at different locations.
- Generate station-wise passenger detection summaries.
- Simulate passenger arrivals, bus movement, and passenger boarding.
- Explore demand-aware bus allocation strategies.
- Evaluate passenger waiting time and transport simulation performance.

## Technologies
- Python
- OpenCV
- Google Colab
- Pandas
- NetLogo
- Computer Vision
- Agent-Based Modeling

## Project Structure
- `computer-vision/` — Image and video processing notebooks.
- `netlogo/` — NetLogo multi-agent simulation model.
- `data/` — Sample passenger-demand CSV files.
- `README.md` — Project documentation.

## Workflow
1. Provide an image or video as input to the Computer Vision pipeline.
2. Detect and count passengers in the supported input.
3. Summarize passenger detections by camera or location.
4. Prepare station-demand data in CSV format.
5. Use demand estimates to inform the NetLogo simulation.
6. Analyze passenger boarding, waiting time, and bus allocation outcomes.

## Current Status
The current prototype includes a passenger-demand CSV workflow and a NetLogo simulation of passenger arrivals, bus movement, and boarding. Image-processing support and video-processing support should be documented according to the functionality implemented in the current Computer Vision notebook.

## Limitations
- Camera IDs have not yet been verified as distinct bus stops.
- Passenger detections across video frames may count the same person more than once.
- Demand mapping and bus allocation are experimental and require further validation.

## Future Improvements
- Improve passenger detection and unique-person tracking.
- Validate station-level demand estimates.
- Integrate image/video analysis directly with NetLogo.
- Compare baseline and demand-aware bus allocation.
- Evaluate waiting time and bus utilization under different scenarios.
