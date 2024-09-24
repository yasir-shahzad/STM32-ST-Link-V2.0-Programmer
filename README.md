# STM32 ST-Link V2.0 Clone - Altium Designer Files
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Commits since latest](https://img.shields.io/github/commits-since/yasir-shahzad/STM32-ST-Link-V2.0-Programmer/latest)](https://github.com/yasir-shahzad/STM32-ST-Link-V2.0-Programmer/commits/master)
[![GitHub issues](https://img.shields.io/github/issues/yasir-shahzad/STM32-ST-Link-V2.0-Programmer.svg)](https://github.com/yasir-shahzad/STM32-ST-Link-V2.0-Programmer/issues)
![Hit Counter](https://visitor-badge.laobi.icu/badge?page_id=yasir-shahzad_STM32-ST-Link-V2.0-Programmer)

If you like **STM32-ST-Link-V2.0** - give it a star, or fork it and contribute!
[![GitHub stars](https://img.shields.io/github/stars/yasir-shahzad/STM32-ST-Link-V2.0-Programmer.svg?style=social&label=Star)](https://github.com/yasir-shahzad/STM32-ST-Link-V2.0-Programmer/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yasir-shahzad/STM32-ST-Link-V2.0-Programmer.svg?style=social&label=Fork)](https://github.com/yasir-shahzad/STM32-ST-Link-V2.0-Programmer/network)

This repository contains the open-source schematic and PCB design files for an ST-Link V2.0 clone, created using Altium Designer. This clone allows you to program and debug STM8 and STM32 microcontrollers.


## Need Help with Embedded Systems or Hardware Design?
I offer professional services for embedded systems design and hardware development at competitive rates starting at **$10/hour**. If you're looking for assistance with your next project, feel free to contact me:

<p align="left">
<a href="https://www.facebook.com/yasirshahzad918/" target="blank"><img align="center" src="path/to/facebook-icon.svg" alt="Facebook Profile" height="30" width="40" /></a>
<a href="https://www.linkedin.com/in/yasirshahzad18/" target="blank"><img align="center" src="path/to/linkedin-icon.svg" alt="LinkedIn Profile" height="30" width="40" /></a>
<a href="https://www.instagram.com/mastermind.pk/" target="blank"><img align="center" src="path/to/instagram-icon.svg" alt="Instagram Profile" height="30" width="40" /></a>
<a href="https://twitter.com/yourprofile" target="blank"><img align="center" src="path/to/twitter-icon.svg" alt="Twitter Profile" height="30" width="40" /></a>
<a href="https://www.fiverr.com/yourprofile" target="blank"><img align="center" src="path/to/fiverr-icon.svg" alt="Fiverr Profile" height="30" width="40" /></a>
<a href="https://www.upwork.com/yourprofile" target="blank"><img align="center" src="path/to/upwork-icon.svg" alt="Upwork Profile" height="30" width="40" /></a>
</p>


## Schematic Diagram
![Schematic Diagram](https://github.com/yasir-shahzad/STM32-ST-Link-V2.0-Programmer/blob/master/images/Schematic.png)

## PCB Layout
![PCB Board](https://github.com/yasir-shahzad/STM32-ST-Link-V2.0-Programmer/blob/master/images/PCB.png)

## 🚀 Features  
- 🔋 **5V power** supplied via USB connector  
- 💻 **USB 2.0 full-speed** compatible interface  
- 🔌 USB Standard A to Mini-B cable  
- 🌐 **SWIM-specific features**:  
  - 1.65V to 5.5V application voltage supported on the SWIM interface  
  - Supports both low-speed and high-speed modes  
  - SWIM programming speed: 9.7 Kbytes/s (low speed), 12.8 Kbytes/s (high speed)  
  - Connection via ERNI standard vertical (ref: 284697/214017) or horizontal (ref: 214012) connector  
  - Pin header or 2.54 mm pitch connector for application connection  
- 🛠️ **JTAG-specific features**:  
  - 1.65V to 3.6V application voltage supported, with 5V-tolerant inputs  
  - Standard 20-pin JTAG connection (2.54 mm pitch)  
- 🔄 **Direct firmware update** (DFU) feature supported  
- 💡 **Status LED** blinks during PC communication  
- 🌡️ Operating temperature: 0°C to 50°C  

## 📋 Requirements  
- 🖥️ **Altium Designer** (or a compatible viewer)  

## 📸 Screenshots 👀  
<table>
  <tr>
    <th>
        <a href="images/Top3D.png" target="_blank">
        <img src='images/Top3D.png' width='200px' alt='Top 3D View' />
        </a>
    </th>
    <th>
        <a href="images/Bottom3D.png" target="_blank">
        <img src='images/Bottom3D.png' width='200px' alt='Bottom 3D View' />
        </a>
    </th>  
    <th>
        <a href="images/Top_Layout.png" target="_blank">
        <img src='images/Top_Layout.png' width='200px' alt='Top Layout' />
        </a>
    </th>
    <th>
        <a href="images/Bottom_Layout.png" target="_blank">
        <img src='images/Bottom_Layout.png' width='200px' alt='Bottom Layout' />
        </a>
    </th>
  </tr>
</table>

## 🚀 Getting Started  
1. **Download the repository**: Click the "Clone or download" button above.  
2. **Open the project**: Use Altium Designer to open the `.PrjPCB` file in the main directory.  
3. **Review the schematics**: Open the `schematic.SchDoc` file to check the electrical connections and components used.  
4. **Examine the PCB layout**: Open the `PCB.PCBDoc` to view the physical layout of the components on the PCB.  
5. **Generate BOM (optional)**: Use Altium Designer's features to generate a Bill of Materials (BOM).  

## 📄 Additional Information  
- **Firmware**: This repository doesn’t include firmware. Get the official ST-Link V2.0 firmware [here](https://github.com/GMMan/st-link-hack/blob/master/upgrade/upgrade.md).  
- **Assembly instructions**: Consider adding detailed instructions for soldering and assembling the PCB (optional).  
- **License**: Specify the open-source license (e.g., MIT License).  

## 🤝 Contributing  
Contributions are welcome! Feel free to submit pull requests with improvements, bug fixes, or new features.
