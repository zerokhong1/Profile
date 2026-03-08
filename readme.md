# Luu Thai

**SLAM & Computer Vision Researcher** — Geometry-aware 3D Gaussian Splatting for Visual SLAM

## Current Research

Developing modifications to [Photo-SLAM](https://github.com/HuajianUP/Photo-SLAM) by integrating  components for improved mapping quality in real-time visual SLAM systems.

**Key contributions:**
- Parallax-based keyframe selection for better multi-view coverage
- Multi-view photometric loss for geometrically consistent Gaussian optimization  
- Geometry consensus loss leveraging depth from triangulation
- Depth consistency regularization for 3D Gaussian maps
- Rigorous 3×3 repeat benchmarking methodology for SLAM non-determinism analysis

**Datasets:** TUM RGB-D (fr1/desk, fr2/xyz, fr3/office) · Replica (room0, room1, office0)  
**Target:** IROS 2026 submission

## Technical Stack

| Domain | Tools |
|--------|-------|
| SLAM | ORB-SLAM3, Photo-SLAM, Visual Odometry, Bundle Adjustment |
| 3D Reconstruction | 3D Gaussian Splatting, NeRF, Multi-view Geometry |
| Deep Learning | PyTorch, Transformer, YOLO, Depth Estimation |
| Languages | Python, C++, CUDA |
| Frameworks | ROS2, OpenCV, Open3D |
| Tools | Gazebo, Docker, Git, conda, CMake |
| Hardware | NVIDIA RTX 5090 (CUDA 12.8), RGB-D cameras |

## Repositories

### 🔬 Research
| Repo | Description |
|------|-------------|
| [photo-slam-triags](https://github.com/zerokhong1/photo-slam-triags) | Geometry-aware Photo-SLAM with TriaGS integration — depth regularization, parallax keyframe selection, multi-view photometric loss |
| [slam-benchmark-tools](https://github.com/zerokhong1/slam-benchmark-tools) | Evaluation pipeline for visual SLAM: multi-run statistical analysis, PSNR/SSIM/LPIPS metrics, non-determinism quantification |

### 🛠️ Projects
| Repo | Description |
|------|-------------|
| [yolov8-detection-ocr](https://github.com/zerokhong1/yolov8-detection-ocr) | Object detection pipeline with YOLOv8 + integrated OCR for document processing |
| [act-imitation-learning](https://github.com/zerokhong1/act-imitation-learning) | Action Chunking with Transformers (ACT) for robotic manipulation — policy learning from demonstrations |

### 📝 Notes & References
| Repo | Description |
|------|-------------|
| [slam-theory-notes](https://github.com/zerokhong1/slam-theory-notes) | Study notes: Bundle Adjustment, loop closure, SE(3)/quaternion representations, factor graphs |

## Publications

- **[In preparation]** Geometry-Aware Mapping for Photo-SLAM with Triangulation-Guided 3D Gaussian Splatting — *targeting IROS 2026*

## Contact

- **LinkedIn:** [linkedin.com/in/congthaineur](https://www.linkedin.com/in/congthaineur)
- **Email:** sunshineforwho@gmail.com
- **Location:** Hanoi, Vietnam
