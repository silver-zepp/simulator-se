# Simulator 2.x SE

This is an alpha release of the `Simulator 2.x`. You can wait for its full release soon or start testing now. Below are the installation instructions for Windows, Linux, and macOS platforms.

The `Simulator 2.x` has these crucial benefits:
1. Does NOT require `sudo` or other administrative privileges
2. Does NOT require a `TUN/TAP` adapter which inherently solves these issues
    - Some VPNs are known to overwrite our `tun` adapter. When that happens the simulator stops working. It can be impossible to figure out the issue.
    - Other VPNs that block LAN visibility firewall the `tun` adapter making it impossible to reach the Emulator
    - The number of supported platforms can be extended now. This should bring our Simulator to more `ARM` based devices and other architectures

In the future, our `firmware patcher` will be integrated into the Simulator for more seamless interaction.

## Table of Contents

- [How to Install on Windows](#how-to-install-on-windows)
- [How to Install on Linux](#how-to-install-on-linux)
- [How to Install on macOS](#how-to-install-on-macos)

## How to Install on Windows

To install Simulator 2.x on Windows:
1. Download and install the current version of Simulator from [our website](https://upload-cdn.huami.com/zeppos/simulator/download/simulator_1.2.4.exe)  
   (you can skip this step if you already have it installed)
2. Unzip the contents of one of the archives from the [Releases](../../releases) page, overwriting the contents.
* by default, on windows, the Simulator is installed under `C:\Users\YOUR_USERNAME\AppData\Local\Programs\`
3. Run the Simulator and install all the necessary Emulators.
4. Finally, run the `simfw-patcher-win.exe` which is located in the same folder as `simulator.exe` and follow the instructions.
5. Done! You should be able to run the Simulator without `TUN/TAP` adapter.

![](./assets/win/sim-win.png)

## How to Install on Linux

To install Simulator 2.x on Linux:
1. Download and install the current version of Simulator from [our website](https://upload-cdn.huami.com/zeppos/simulator/download/simulator_1.2.4_amd64.deb)  
   (you can skip this step if you already have it installed)
2. Unzip the contents of one of the archives from the [Releases](../../releases) page, overwriting the contents.
* by default, on linux, the Simulator is installed under `/opt/`
3. Run the Simulator and install all the necessary Emulators.
4. Finally, run the `simfw-patcher-linux` which is located in the same folder as `simulator`'s executable and follow the instructions.
* you might have to make pather executable with `chmod +x simfw-patcher-linux`
5. Done! You should be able to run the Simulator without `sudo` and without `TUN/TAP` adapter.

![](./assets/linux/sim-linux.png)

## How to Install on macOS

To install Simulator 2.x on macOS:
1. Download and install the current version of Simulator from [our website](https://upload-cdn.huami.com/zeppos/simulator/download/simulator_1.2.4.dmg)  
   (you can skip this step if you already have it installed)
2. Extract the contents of one of the archives from the [Releases](../../releases) page, overwriting the contents.
* by default, on mac, the Simulator is installed under `Applications/simulator`
3. Run the Simulator and install all the necessary Emulators.
4. Finally, run the `simfw-patcher-mac` that is located next to the `Contents` folder and follow the instructions.
5. Done! You should be able to run the Simulator without `sudo` and without `TUN/TAP` adapter.

![](./assets/mac/sim-mac-1.png)  
![](./assets/mac/sim-mac-2.png)  
![](./assets/mac/sim-mac-3.png)  
![](./assets/mac/sim-mac-4.png)
