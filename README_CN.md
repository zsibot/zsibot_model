# 智身机器人 URDF 模型

[![License: BSD‑3-Clause](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](LICENSE)  
> 📄 **English Version**：[README.md](./README.md)

## 简介

本仓库提供 **ZsiBot** 机器人的 URDF 模型及对应的 Mesh 文件，供二次开发者用于 ROS / Gazebo / RViz 仿真和可视化。

## 目录架构

```text
zsibot_model/
├── LICENSE
├── README.md
├── README_CN.md
└── zsl-1/
    ├── urdf/            # URDF definitions (e.g. DOG.urdf, DOG.xacro)
    └── meshes/          # STL mesh files for each link
