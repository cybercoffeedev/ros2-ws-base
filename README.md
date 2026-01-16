<div align="center">
  <h1>ROS 2 Workspace</h1>
</div>

### A base ROS 2 workspace configuration with Dev Container support.

This repository provides a pre-configured environment for Robot Operating System (ROS) development using Dev Containers.

> Support for Dev Containers is currently limited to Linux-based systems with NVIDIA GPUs.

---

### Features

* **GUI Support:** Ready to run graphical tools.
* **Hardware Access:** Gamepads and joysticks are supported via `/dev/input`.

### Prerequisites

Before starting, ensure you have the [NVIDIA Container Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) installed and configured correctly on your host system.

**Display Permissions:** To allow graphical tools (like RViz or Gazebo) to launch from the container, grant local X11 permissions by running the following command on your host:
```
xhost +local:
```

*For more detailed information about the container configuration, please refer to the [official ROS 2 documentation](https://docs.ros.org/en/kilted/How-To-Guides/Setup-ROS-2-with-VSCode-and-Docker-Container.html).*