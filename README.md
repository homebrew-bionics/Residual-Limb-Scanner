# Residual limb Scanner

![windows](https://img.shields.io/badge/Windows-7%20%7C%2010-blue)
![Kinect](https://img.shields.io/badge/Kinect-v1%20%7C%20v2-blueviolet)

A WPF application for scanning residual limb of the amputee.

![rlscanner](https://github.com/homebrew-bionics/Residual-Limb-Scanner/blob/main/rlscanner.png)

# Installation

* Installation files can be found within [./installer](https://github.com/homebrew-bionics/Residual-Limb-Scanner/tree/main/Installer)
* Run ``setup.exe``
* Copy ``KinectFusion180_64.dll`` to installation path (Default: C:\Users\name\AppData\Local\Apps\2.0)

# Usage

![usage](https://github.com/homebrew-bionics/Residual-Limb-Scanner/blob/main/ui.png)

* Minimum and maximum **depth** can be adjusted to define a region of interest for scanning in 3D space.
* **Voxel density** can be increased to obtain results with high accuracy at the cost of computational power.
* **Volume integration weight** can be tweaked to reduce noise in the data.

# Results

<img src="https://github.com/homebrew-bionics/Residual-Limb-Scanner/blob/main/results.gif" alt="results" width="900"/>
