# ros2_nvidia_isaac
Native Install Isaac Sim + ROS 2 on Ubuntu 22.04 or Ubuntu 24.04

## System Prerequisites
For a local/native setup, use a machine with:
- Ubuntu 22.04 or Ubuntu 24.04
- NVIDIA RTX 3050 or higher
- More than 6 GB GPU VRAM

## Using this manual: https://docs.isaacsim.omniverse.nvidia.com/5.1.0/installation/quick-install.html, download Isaac Sim using this link:
https://download.isaacsim.omniverse.nvidia.com/isaac-sim-standalone-5.1.0-linux-x86_64.zip

After downloading, extract it:
unzip isaac-sim-standalone-5.1.0-linux-x86_64.zip

**Install ROS 2 with One-Line Script**
Repository:
https://github.com/runtimerobotics/ros2_oneline_install

In the above one-line script, the following steps have been done:
Step 1: Configure your Ubuntu repositories
Step 2: Add ROS 2 repository and keys
Step 3: Updating the Ubuntu package index. This will take a few minutes, depending on your network connection
Step 4: Install ROS. You pick how much of ROS you would like to install:
     1. Desktop Full Install: (Recommended): Everything in Desktop plus 2D/3D simulators and 2D/3D perception packages.
     2. Desktop Install: Everything in Desktop.
     3. ROS-Base: (Bare Bones) ROS packaging, build, and communication libraries. No GUI tools.
     Enter your install (Default is 1) [1/2/3]: 1
Step 5: Setting ROS Environment. This will add the ROS environment to .bashrc
Step 6: Testing ROS installation, checking ROS version

**Install ROS 2 Jazzy:**
wget -c https://raw.githubusercontent.com/runtimerobotics/ros2_oneline_install/main/ros2_install_jazzy.sh && chmod +x ./ros2_install_jazzy.sh && ./ros2_install_jazzy.sh

**Install ROS 2 Humble:**
wget -c https://raw.githubusercontent.com/runtimerobotics/ros2_oneline_install/main/ros2_install_humble.sh && chmod +x ./ros2_install_humble.sh && ./ros2_install_humble.sh
