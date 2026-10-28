# Vision-Based Public Transport Flow Analysis & Multi-Agent Simulation

## Overview
This semester project combines computer vision and agent-based modeling to explore passenger demand estimation and bus allocation in public transport systems.

## Objectives
- Detect and count passengers from video.
- Summarize passenger detections by camera or station.
- Simulate passengers, buses, and bus stations in NetLogo.
- Explore how passenger demand can inform bus allocation.
- Evaluate passenger boarding and waiting-time metrics.

## Technologies
- Python
- OpenCV
- Google Colab
- Pandas
- NetLogo

## Project Structure
- `computer-vision/` — Computer vision notebook
- `netlogo/` — Agent-based simulation
- `data/` — Sample station-demand CSV
- `README.md` — Project documentation

## Current Status
The prototype generates station-wise passenger detection summaries and simulates passenger arrivals, bus movement, and boarding in NetLogo.

## Limitations
Camera IDs have not yet been verified as distinct bus stops. Passenger detections across video frames may include repeated observations of the same person. The current station mapping and bus-allocation logic are experimental.

## Future Improvements
- Validate camera-to-station mapping.
- Improve unique passenger tracking.
- Import demand data directly into NetLogo.
- Compare baseline and demand-based bus allocation.
- Evaluate average waiting time and bus utilization.

## How to Run
1. Open the computer vision notebook in Google Colab.
2. Provide a suitable video and run the notebook cells.
3. Review the generated station-demand CSV.
4. Open the NetLogo model in NetLogo.
5. Run `setup`, then `go`, and observe the simulation.
