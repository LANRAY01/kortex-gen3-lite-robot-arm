# Kortex-gen3-lite-robot-arm Description

This repository contains the **URDF** files  for visualizing and simulating the Kortex-gen3-lite robot arm in  **RViz2**.
---

## Requirements
- **Ros2 Humble or other versions**
- **urdf_tutorial** package
- **RViz2**
## How to use the repo

### 1. Clone the Repo

Clone this repository into your workspace:

```bash
git clone https://github.com/LANRAY01/kortex-gen3-lite-robot-arm

```
### 2. Create your Workspace

Move the kortex-gen3-lite to your workspace

### 3. Check for Dependencies

Verify that your workspace detects the package:

```bash
colcon list
```

If dependencies are missing, make sure to install them before proceeding.

### 4. Build the Package

```bash
colcon build
```

### 5. Source the Setup File

After building, source your workspace environment:

```bash
source install/setup.bash

