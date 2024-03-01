![Microchip logo](https://raw.githubusercontent.com/wiki/Microchip-MPLAB-Harmony/Microchip-MPLAB-Harmony.github.io/images/microchip_logo.png)
![Harmony logo small](https://raw.githubusercontent.com/wiki/Microchip-MPLAB-Harmony/Microchip-MPLAB-Harmony.github.io/images/microchip_mplab_harmony_logo_small.png)
<img src="https://avatars.githubusercontent.com/u/45752777?s=200&v=4" height="56" alt="RT-Labs logo small">

# MPLAB® Harmony 3 Industrial Communication Packages

MPLAB® Harmony 3 is an extension of the MPLAB® ecosystem for creating
embedded firmware solutions for Microchip 32-bit SAM and PIC® microcontroller
and microprocessor devices.  Refer to the following links for more information.

- [Microchip 32-bit MCUs](https://www.microchip.com/design-centers/32-bit)
- [Microchip 32-bit MPUs](https://www.microchip.com/design-centers/32-bit-mpus)
- [Microchip MPLAB X IDE](https://www.microchip.com/mplab/mplab-x-ide)
- [Microchip MPLAB® Harmony](https://www.microchip.com/mplab/mplab-harmony)
- [Microchip MPLAB® Harmony Pages](https://microchip-mplab-harmony.github.io/)

Microchip's Harmony 3 Industrial Communication Packages is a collection of expansive frameworks designed to facilitate seamless and efficient integration of Ethernet connectivity into industrial applications. These packages leverages the robust capabilities of Microchip's hardware, ensuring reliable data transmission and network resilience vital for industrial environments. Aimed at developers working on sophisticated control systems, the packages provide a comprehensive set of drivers, and example applications to streamline the development process, enhancing productivity and reducing time to market.

Explore the GitHub repositories dedicated to Harmony 3 Industrial Communication Solutions for in-depth code examples, and support resources tailored to advance your projects with Microchip technology.


- [Release Notes](release_notes.md)
- [License](license.md)
- [MPLAB® Harmony 3 industrial Wiki](https://github.com/rtlabs-com/mplab-harmony-demo/wiki)
- [MPLAB® Harmony 3 industrial Docs](https://microchip-mplab-harmony.github.io/wireless_wifi)

## Single-Protocol Support

### EtherCAT
<a href="https://github.com/rtlabs-com/p-net"> <img src="https://rt-labs.com/wp-content/uploads/ethercat-technology-group-vector-logo.svg" alt="EtherCAT" style="width:150px;"/> </a>      

EtherCAT (Ethernet for Control Automation Technology) is known for its high-speed data exchange and real-time capabilities, making it ideal for automation tasks requiring swift and efficient communication. Its ability to operate over Ethernet facilitates straightforward integration into existing networks, reducing infrastructure costs and complexity.

Microchip MPLAB Harmony offers a variety of application examples for EtherCAT communication across several supported device families. For specific EtherCAT application examples, refer to the following repositories under the Microchip-MPLAB-Harmony GitHub project:

|        Family       | Repository              |
|:-------------------:|-------------------------|
| PIC32MX             | [ethercat_apps_pic32mx](link)     |
| PIC32MZEF/PIC32MZDA | [ethercat_apps_pic32mz](link)     |
| SAMA5D2             | [ethercat_apps_sam_a5d2](link)    |
| SAME5x              | [ethercat_apps_sam_e5x](link)     |
| SAMRH71             | [ethercat_apps_sam_rh71](link)    |


### Profinet
<a href="https://github.com/rtlabs-com/p-net"> <img src="https://rt-labs.com/wp-content/uploads/profinet-vector-logo-1.svg" alt="Profinet" style="width:150px;"/> </a>   

Profinet is an industry-standard for automation technology, offering advanced features for automation tasks and system integration. It supports real-time data exchange, is highly scalable, and provides mechanisms for ensuring data integrity and network security. Profinet enables seamless integration of automation devices, enhancing interoperability and system cohesion.

|        Family       | Repository              |
|:-------------------:|-------------------------|
| LAN9662 | [profinet_apps_lan9662](link)     |

### EtherNet/IP
<a href="https://github.com/rtlabs-com/p-net"> <img src="https://rt-labs.com/wp-content/uploads/ethernet-ip-vector-logo-thin-1.svg" alt="Profinet" style="width:150px;"/> </a>   

EtherNet/IP utilizes standard Ethernet and IP protocols to provide industrial networking solutions, enabling devices from different manufacturers to communicate within the same network. It supports a wide range of applications, from simple control to complex automation systems, facilitating device integration and data sharing across the network.

|        Family       | Repository              |
|:-------------------:|-------------------------|
| PIC32MX             | [ethernetip_apps_pic32mx](link)     |
| PIC32MZEF/PIC32MZDA | [ethernetip_apps_pic32mz](link)     |

### Modbus
<a href="https://github.com/rtlabs-com/p-net"> <img src="https://rt-labs.com/wp-content/uploads/modbus-organization-inc-vector-logo-1.svg" alt="Profinet" style="width:150px;"/> </a>   

Modbus is a widely used communication protocol in the industrial sector, known for its simplicity and reliability. It supports communication among many devices connected to the same network, ideal for monitoring and controlling industrial equipment. Modbus is versatile, easy to deploy, and supports both serial and TCP/IP communications, making it suitable for a wide range of industrial applications.

|        Family       | Repository              |
|:-------------------:|-------------------------|
| PIC32MX             | [modbus_apps_pic32mx](link)     |
| PIC32MZEF/PIC32MZDA | [modbus_apps_pic32mz](link)     |

## Multi-Protocol Support

### U-Phy
<a href="https://github.com/rtlabs-com/p-net"> <img src="https://rt-labs.com/wp-content/uploads/u-phy.svg" alt="Profinet" style="width:150px;"/> </a>   

U-Phy on LAN9255 CPU with LAN9303 (Switch)

U-Phy, operating on the LAN9255 CPU in conjunction with the LAN9303 switch, offers a versatile multi-protocol solution that simplifies Ethernet connectivity integration into industrial systems. This unique setup supports a wide array of protocols, including Profinet, EtherCAT, and EtherNet/IP, enabling seamless communication across different industrial devices and networks.

|        Family       | Repository              |
|:-------------------:|-------------------------|
| LAN9255             | [U-Phy product page](https://rt-labs.com/u-phy)     |

Key features of U-Phy include:

 - Ease of Use: No prior protocol expertise is required to deploy U-Phy, making it accessible to a broader range of users and applications.
 - Industrial Compliance: As a pre-certified solution, U-Phy ensures compliance with industry standards, offering optimal performance and peace of mind from the outset.
 - Rapid Deployment: The evaluation kit allows for immediate access to multiple industrial protocols, facilitating quick and straightforward system testing and integration.
 - Open-Source Hardware Platform: U-Phy's commitment to open-source principles means users maintain complete control over their hardware production, fostering innovation and reducing costs.

For comprehensive details on U-Phy's capabilities, protocol support, and deployment options, visit RT-Labs' dedicated pages.
