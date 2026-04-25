<img width="1699" height="1744" alt="tp_online_gui" src="https://github.com/user-attachments/assets/e87215f7-aadb-4134-9965-3808941b1591" />


## ✨ Key Features

* 🎬 **True 12-bit ProRes 4444 output:** It dynamically matches source input
* 🎞️ **Professional Formats & ProRes:** Supports standard `.mp4`/`.mkv` as well as `.mov` Apple ProRes 422 HQ and ProRes 4444 outputs. Also supports direct `.png`/`.exr`/`.tiff` image sequence I/O.
* 🎬 **Scene-Aware Interpolation:** with PySceneDetect (Adaptive & Content detection) to map video cuts. It dynamically halts interpolation at scene boundaries, seamlessly copying edge-frames instead of morphing between completely different shots.
* 🧠 **Practical-RIFE AI:** Utilizes `hzwer/Practical-RIFE` for high-quality, motion-compensated frame generation.
* 📐 **Resolution Independent:** Safely processes *any* resolution or aspect ratio (1080p, 4K, 4:3, Vertical 9:16, or irregular crops) using dynamic tensor edge-padding.
* ⚙️ **Fractional Framerate Math:** Calculates variable-rate timesteps to handle complex frame rate conversions perfectly (e.g., converting 23.976 fps to 59.94 fps).
* 🚀 **VRAM Optimized:** Runs in `fp16` (Half-precision) on CUDA by default for faster renders and lower GPU memory consumption.
* 📦 **Zero-Config Setup:** Automatically downloads `ffmpeg`/`ffprobe` and fetches the necessarymodel weights 



<img width="1687" height="547" alt="target_fps" src="https://github.com/user-attachments/assets/47111353-5ba8-40c3-a4c3-3c40f7a84ccf" />
