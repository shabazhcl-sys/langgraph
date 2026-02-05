# LiDAR-Based Object Detection (Camera + LiDAR Fusion Utilities)

A Python project for running LiDAR-based object detection and related utilities such as model inference, visualization, test detection scripts, and traffic metrics analysis.  
This repository contains scripts to prepare data, run inference, visualize point clouds/detections, and compute traffic analytics.

---

## 📌 Features

- **Model Inference** on LiDAR / fused data (`model_inference.py`)
- **LiDAR loading & preprocessing** (`lidar_loader.py`)
- **Visualization utilities** for point cloud & detection overlays (`visualizer.py`, `normal_visualization.py`)
- **Detection testing** pipeline (`test_detection.py`)
- **Traffic metrics / analytics** (`traffic_analyzer.py`)
- **Dataset / requirements helper scripts** (`requirements.txt`, `tempCodeRunnerFile.py`)

---

## 🧱 Repository Structure

| File | Purpose |
|------|---------|
| `main.py` | Main entry point to run core workflow (inference / pipeline execution) |
| `lidar_loader.py` | Load LiDAR point clouds and perform preprocessing |
| `model_inference.py` | Run the object detection model inference |
| `visualizer.py` | Visualize point clouds and detection results |
| `normal_visualization.py` | Alternate visualization / debugging visualizations |
| `test_detection.py` | Script to test detection pipeline end-to-end |
| `traffic_analyzer.py` | Compute traffic metrics from detections (counts, flow, etc.) |
| `requirements.txt` | Python dependencies |
| `.gitignore` | Git ignored files |
| `info.txt` | Notes / metadata about dataset or usage (project-specific) |
| `tempCodeRunnerFile.py` | VSCode temporary runner file (safe to remove) |

> Tip: If `tempCodeRunnerFile.py` is not needed, consider deleting it and adding it to `.gitignore`.

---

## 🚀 Getting Started

### 1) Clone the repository
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
