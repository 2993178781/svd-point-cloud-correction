Dataset Description

The repository contains:

Simulated point cloud correction results under different error settings
Control point files used for sparse-control-point correction
Experimental result tables
Source code for SVD-based global correction and local optimization
Small processed sample point cloud data for demonstration

The simulated experiments include:

XY-plane displacement
XY-plane deformation
Z-axis tilt
Z-axis protrusion
Synthetic deformation

The original WHU-TLS dataset should be obtained from its original provider according to its data usage policy. This repository only provides processed sample data, control point files, experimental results, and implementation code.

Evaluation Metrics

The following metrics are used:

Chamfer Distance (CD)
Root Mean Square Error (RMSE)
Mean Absolute Distance (MAD)
Overlap Degree (OD)
Usage
python src/run_demo.py
Citation

If you use this repository, please cite:

Li Zheng, Guanqi Wang, Yuchen Lin, and Zhukun Li.
Enhancing Non-Rigid Point Clouds through Singular Value Decomposition: A Comprehensive Approach Integrating Global and Local Optimization.

License

The source code is released under the MIT License.
The processed data and experimental results are provided for academic research purposes.

Contact

Corresponding author: Zhukun Li
Email: lizhukun@whu.edu.cn
