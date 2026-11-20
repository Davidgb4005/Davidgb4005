# Hi, I'm Dave Burgoin

I'm an engineering student focused on embedded firmware and Embedded Linux. I
enjoy working close to the hardware boundary: device drivers, data acquisition,
reliable C and C++, Linux services, and the build systems that turn source code
into deployable images.

## Featured work

### [ESP32-C6 Vehicle Current Monitor](https://github.com/Davidgb4005/current-monitor)

Component-oriented ESP-IDF firmware for monitoring a vehicle alternator, dual
batteries, and auxiliary systems. It combines ADC acquisition, persistent
calibration, an I2C display, FreeRTOS tasks, Wi-Fi, and an embedded diagnostics
dashboard.

### [Edge Health Agent](https://github.com/Davidgb4005/edge-health-agent)

A dependency-light C service that reads Linux health metrics directly from
procfs and sysfs. It includes fixture-backed tests, CMake cross-compilation,
continuous integration, and a hardened systemd unit.

### [Yocto Edge Demo Layer](https://github.com/Davidgb4005/meta-edge-demo)

A Yocto layer that packages the health agent into a read-only QEMU ARM64 image.
It demonstrates a pinned BitBake recipe, custom image composition, systemd
integration, reproducible kas configuration, and OEQA runtime testing.

## Tools and technologies

- **Firmware:** C, C++, ESP-IDF, FreeRTOS, bare-metal peripherals
- **Embedded Linux:** Yocto Project, BitBake, systemd, procfs/sysfs, QEMU
- **Build and quality:** CMake, Git, GitHub Actions, unit testing
- **Interfaces:** I2C, SPI, UART, ADC, GPIO, TCP/IP, HTTP

I'm currently looking for embedded firmware and Embedded Linux opportunities
where I can contribute across the boundary between hardware and software.
