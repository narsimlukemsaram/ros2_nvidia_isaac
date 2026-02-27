# ros2_nvidia_isaac
Native Install Isaac Sim + ROS 2 on Ubuntu 22.04 or Ubuntu 24.04

**System Prerequisites**
For a local/native setup, use a machine with:
- Ubuntu 22.04 or Ubuntu 24.04
- NVIDIA RTX 3050 or higher
- More than 6 GB GPU VRAM

**Download Isaac Sim using this link: **
https://download.isaacsim.omniverse.nvidia.com/isaac-sim-standalone-5.1.0-linux-x86_64.zip

After downloading, extract it:
unzip isaac-sim-standalone-5.1.0-linux-x86_64.zip

**Install ROS 2 with One-Line Script**
Repository:
https://github.com/runtimerobotics/ros2_oneline_install

**Install ROS 2 Jazzy:**
wget -c https://raw.githubusercontent.com/runtimerobotics/ros2_oneline_install/main/ros2_install_jazzy.sh && chmod +x ./ros2_install_jazzy.sh && ./ros2_install_jazzy.sh

**Install ROS 2 Humble:**
wget -c https://raw.githubusercontent.com/runtimerobotics/ros2_oneline_install/main/ros2_install_humble.sh && chmod +x ./ros2_install_humble.sh && ./ros2_install_humble.sh
