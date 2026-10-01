# Hi, I'm Artem 👋

Embedded-systems engineer from Russia 🇷🇺. I work with ARM single-board computers — **Orange Pi Zero 3W (Allwinner A733)**, **Orange Pi 4 Pro** and **Raspberry Pi** — and publish everything I figure out as open, reproducible, step-by-step guides.

## 🔧 Focus areas

- Linux kernel & device-tree work on Allwinner (A733) and Broadcom platforms
- GPU / Vulkan / OpenGL ES enablement (PowerVR BXM-4-64)
- PCIe, NVMe and USB-storage boot — including booting with **no SD card at all**
- Displays on SBCs: HDMI timing, SPI/DSI panels, touch controllers
- Distro porting & fixes (Debian 12 → 13), kernel modules, packaging
- Portable / battery-powered SBC builds and custom input devices

## 🟠 Orange Pi

- **[orangepi-zero3w-gpu-pcie](https://github.com/Haidegger22/orangepi-zero3w-gpu-pcie)** — OpenGL ES 3.2 + Vulkan 1.3 + PCIe 3.0 working on the Allwinner A733
- **[orangepi4pro-nvme-boot-no-sd](https://github.com/Haidegger22/orangepi4pro-nvme-boot-no-sd)** — Orange Pi 4 Pro booting entirely from NVMe with no SD card (patched U-Boot)
- **[opi-zero3w-m5hub](https://github.com/Haidegger22/opi-zero3w-m5hub)** — Zero 3W + M5Stack PaHub: joystick, scroll unit and CardKB as a portable input hub
- **[orangepi-zero3w-gpu-npu-vpu-debian11](https://github.com/Haidegger22/orangepi-zero3w-gpu-npu-vpu-debian11)** — GPU / VPU / NPU enablement on Debian 11
- **[orangepi-zero3w-nvme-boot](https://github.com/Haidegger22/orangepi-zero3w-nvme-boot)** — SD + NVMe hybrid boot over USB (ASM2364 / JMS583)
- **[opi-zero3w-hid-multitouch-fix](https://github.com/Haidegger22/opi-zero3w-hid-multitouch-fix)** — `hid-multitouch` kernel module fix

  …plus step-by-step guides on HDMI timing, SPI displays (ST7796S), Bluetooth HID, Chromium optimization, CPU-temperature panel, mihomo/VPN setup and the Debian 12 → 13 migration.

## 🍓 Raspberry Pi

- **[pi4-scroll-unit](https://github.com/Haidegger22/pi4-scroll-unit)** — M5Stack Scroll Unit on Raspberry Pi 4 as a virtual mouse
- **[zero2w-terminal-menu](https://github.com/Haidegger22/zero2w-terminal-menu)** — dynamic terminal launcher for Pi Zero 2W (date, time, CPU temperature)
- **[pi-dual-display](https://github.com/Haidegger22/pi-dual-display)** — Raspberry Pi 4 dual-display setup (DSI 4.3" + HDMI)
- **[pi4-overclock-experiments](https://github.com/Haidegger22/pi4-overclock-experiments)** — Raspberry Pi 4 overclocking parameters and measured results
- **[zero2w-spotpear-3.5inch-lcd-g-st7796s](https://github.com/Haidegger22/zero2w-spotpear-3.5inch-lcd-g-st7796s)** — SpotPear 3.5" SPI display on Pi Zero 2W

## 📱 Android & apps

- **[android-weather-widget](https://github.com/Haidegger22/android-weather-widget)** — погодный виджет 5×1 для Android: подробное окно с почасовкой и 7 днями, выбор города, сборка APK на ARM без Gradle (aapt2 → javac → d8 → apksigner)

## 🛠 Other projects

- **ClawPuter** — pixel desktop companion for the M5Stack Cardputer
- **meshcore-m5stack-c6l** — MeshCore firmware for M5Stack Unit C6L (ESP32-C6 + SX1262)
- **deepseek-widget-build**, **jarvis-chat**, **mc-featured-skin**

## 🧰 Home tools

- **[opi-zero3w-prizrak-box](https://github.com/Haidegger22/opi-zero3w-prizrak-box)** — прокси-клиент Prizrak-Box на Zero 3W: ядро mihomo, автозапуск, проброс портов
- **[opi-zero3w-reticulum](https://github.com/Haidegger22/opi-zero3w-reticulum)** — связь по Reticulum/LXMF через LoRa-меш на Zero 3W
- **[opi-zero3w-desktop-widgets](https://github.com/Haidegger22/opi-zero3w-desktop-widgets)** — виджеты рабочего стола (погода, температура платы) для Zero 3W с экраном 1024×600

## 📬 Contact

- Telegram: [@Haidegger22](https://t.me/Haidegger22)

Open to collaboration on ARM SBC testing, reviews and hardware bring-up.
