## List of Supported VLP versions

Renesas provides the basic software required for the industrial segment as the verified software package. Renesas also provides the multimedia package for installing H.264/H.265 Video codec and graphics (OpenGL ES) function into the RZ MPU BSP (Board Support Package).
Please go to the page from the link that indicates the version of VLP in the table below, download the package and use it.

{{ read_csv('docs/list_of_vlp_versions/_tables/basic_table.csv') }}

!!! note
    Each VLP maintenance will be finished when the maintenance of corresponding CIP Linux Kernel version is completed.  
    Use of the latest version VLP is recommended.  
    Please refer to [CIP Wiki](https://wiki.linuxfoundation.org/civilinfrastructureplatform/start) for CIP Linux kernel maintenance periods.

**The packages for the features you want to use can be downloaded from the list below:**

- [**RZ MPU Security Package**](https://www.renesas.com/software-tool/rz-mpu-security-package-linux-os)  
This package is to add Security functions (Secure Boot, Trusted Execution Environment, Hardware Cryptographic IP, Secure Debug, Security Configurator) to RZ MPU.

- [**RZ Multi-OS Package**](https://www.renesas.com/software-tool/rz-multi-os-package)  
This package is the software package consisting of RZ/G Flexible Software Package (FSP) as software package for Renesas MCU with Arm® Cortex-M Core and OpenAMP as standardization API of framework for interprocessor communication for developing multi OS solution.

- **HTML5 Package**  
HTML5 enables rich HMI development based on advanced Web technologies including JavaScript.

    - [**Chromium Package**](https://www.renesas.com/software-tool/rz-mpu-html5-chromium-package-verified-linux-packages)    
This package provides additional Chromium functions (rendering engine: Blink).
     
    - [**Gecko Package**](https://www.renesas.com/software-tool/rz-mpu-html5-gecko-package-verified-linux-packages-510-cip)    
This package provides additional rendering engine Gecko.

- [**Qt6 Package**](https://www.renesas.com/software-tool/rz-mpu-qt-package)  
This package is for integrating Qt, a cross-platform GUI application development framework. (This package provides for VLP v4. VLP v3 includes Qt5.6.3 for VLP.)

- [**Industrial Software Packages**](https://www.renesas.com/software-tool/rzt2h-and-rzn2h-industrial-software-packages)  

    - **Industrial Network Package**  
Provides examples for using industrial Ethernet protocols and frameworks to accelerate Ethernet communication.

    - **Time-sensitive Network Package**  
Offers examples for using TSN technologies, enabling real‑time communication over Ethernet.

    - **XDP Package**  
Includes examples for using XDP, a high‑performance Linux kernel packet‑processing framework designed for efficient, low‑latency network handling.

    - **OpenPLC Package**  
Explains how to install OpenPLC and the OpenPLC Runtime on both a Windows PC and the evaluation board.

    - **CODESYS Package**  
Provides instructions for installing CODESYS and the CODESYS Runtime on a Windows PC and the evaluation board.
