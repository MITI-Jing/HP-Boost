# HP-Boost installation

## Z by HP Boost (Pro) User Guide
https://docs.google.com/document/d/1hNgMx-WFr1ZOJkdpgL8DPtn6SO2yGiw7wrpuQea74lc/pub#h.k8zysnrfjwv8

## Preconditions for running a Client app
The following are necessary to use a remote GPU:

Windows
Windows 10/11

If you're running on a virtual machine with graphics drivers that don't support Vulkan then you must install the Vulkan Runtime separately.  Download and install https://sdk.lunarg.com/sdk/download/latest/windows/vulkan-runtime.exe

Linux
Ubuntu 20.04 or greater, Debian 11 or greater
The following packages must be installed:
libatomic1
libnuma1
These can be installed by running the following command:


 apt update && apt install libatomic1 libnuma1

## Preconditions for running a GPU agent
The following are necessary to host a remote GPU:


On all platforms an NVIDIA GPU with an installed driver version 535 or greater, and a CUDA driver version 12.2 through to 12.4.

Windows
Windows 10/11
Linux
Ubuntu 20.04 or greater, Debian 11 or greater
The following packages installed:
libatomic1
libnuma1
libvulkan1
libgl1
libglib2.0-0
These can be installed by running the following command:

apt update && apt install libvulkan1 libgl1 libglib2.0-0 libatomic1 libnuma1
