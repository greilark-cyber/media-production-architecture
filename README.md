# High-Fidelity Media Production Architecture
### Powered by NVIDIA NVENC

This repository documents a live-switching environment designed for high-performance visual storytelling and technical demonstrations.

## 🛠️ The Implementation
* **Hardware:** 4x concurrent camera capture via HDMI-to-PCIe interfaces.
* **Acceleration:** 100% video encoding offload to the **NVIDIA NVENC** SIP block.
* **Visual Logic:** Custom scene-switching logic designed to minimize CPU overhead while maintaining 94% system efficiency.

## 📈 TCO & Performance
By utilizing specialized NVIDIA hardware for encoding, I achieved a stable 1080p60 stream with <5% CPU utilization. This setup demonstrates the value of hardware-software synergy in media-intensive environments, ensuring zero dropped frames during high-stakes technical presentations.

### 📁 Documents
* [Technical Solution Brief - NVENC Optimization](./sdr-sessions-multi-camera-move-demo.pdf)
* 30-second clip at [twitch.tv/greilark](https://www.twitch.tv/videos/2700985643)
