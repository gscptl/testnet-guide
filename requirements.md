## Spacemesh App Requirements - Spacemesh 0.1 Release

### Minimum System Requirements

- A computer with modern Intel or AMD multi-core CPU (3 cores / 6 native threads).
- One of the following operating systems: Windows 10 (Home or Pro), macOS, Ubuntu 12.04, Fedora 21, Debian 8.
- 6 GB RAM.
- 150 GB free space on a magnetic HDD or SSD.
- An always-on, unmetered Internet connection capable of 5 mbps download and 1 mbps upload.
- Network configuration that allows the App to accept incoming TCP and UDP connections on port 7153.
- Windows 10 Home, OS X or Linux.

---

### Recommended System Requirements

- A desktop computer with modern Intel or AMD multi-core CPU (4 cores / 8 native threads or better).
- 8 GB RAM.
- 350GB free space on a magnetic HDD or SSD.
- An always-on, unmetered Internet connection capable of 10 mbps download and 1 mbps upload.
- Windows 10 Home, OS X or Linux.
### Linux Systems
> The Spacemesh App is an Electron App. It is supported on any Linux distro that supports [Electron apps](https://electronjs.org/docs/tutorial/support).

## Operational Notes

### CPU Usage
As long as your system and configuration meets the recommended requirements, ongoing utilization of your CPU by the Spacemesh App should be limited during normal operation (after the initial setup phase) to 2 CPU cores.

### Network Configuration
Your network should allow the App to accept incoming connections on UDP port 7153 and on TCP port 7153 and your computer firewall should not block incoming UDP and TPC packets on this port. The App attempts to automatically configure your network using UPnP. In some cases you may need to configure your router and firewall manually. Follow [this guide](netconfig.md) to configure your network.

### Laptop Usage
You can install the App, run a Smesher and produce blocks on your laptop if it meets the minimum system requirements. However, you will need to make sure you leave your laptop open and connected to power and to the Internet 24/7.

Occasionally shutting down your laptop or the App may prevent you from Smeshing blocks and from earning Smeshing rewards.
