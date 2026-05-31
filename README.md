# SVD Point Cloud Correction

This repository provides the code, control point files, processed sample data, and experimental results for the manuscript:

**Enhancing Non-Rigid Point Clouds through Singular Value Decomposition: A Comprehensive Approach Integrating Global and Local Optimization**

## Overview

This study proposes a non-rigid point cloud correction method using a small number of control points. The method integrates global correction and local optimization. In the global correction stage, singular value decomposition (SVD) is used to estimate rotation and translation parameters. In the local optimization stage, each point is adaptively corrected according to its spatial relationship with the control points.

## Repository Structure

```text
svd-point-cloud-correction/
├── README.md
├── LICENSE
├── data/
│   ├── control_points/
│   ├── results/
│   └── sample_data/
├── src/
│   ├── global_correction_svd.py
│   ├── local_optimization.py
│   ├── evaluation_metrics.py
│   └── run_demo.py
└── docs/
    ├── data_description.md
    └── usage.md
```

## Dataset Description

The repository contains:

- Simulated point cloud correction results under different error settings
- Control point files used for sparse-control-point correction
- Experimental result tables
- Source code for SVD-based global correction and local optimization
- Small processed sample point cloud data for demonstration

The simulated experiments include:

- XY-plane displacement
- XY-plane deformation
- Z-axis tilt
- Z-axis protrusion
- Synthetic deformation

The original WHU-TLS dataset should be obtained from its original provider according to its data usage policy. This repository only provides processed sample data, control point files, experimental results, and implementation code.

## Evaluation Metrics

The following metrics are used:

- Chamfer Distance (CD)
- Root Mean Square Error (RMSE)
- Mean Absolute Distance (MAD)
- Overlap Degree (OD)

## Usage

```bash
python src/run_demo.py
```

## Citation

If you use this repository, please cite:

Li Zheng, Guanqi Wang, Yuchen Lin, and Zhukun Li.  
Enhancing Non-Rigid Point Clouds through Singular Value Decomposition: A Comprehensive Approach Integrating Global and Local Optimization.

## License

The source code is released under the MIT License.  
The processed data and experimental results are provided for academic research purposes.

## Contact

Corresponding author: Zhukun Li  
Email: lizhukun@whu.edu.cn
