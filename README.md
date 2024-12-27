# Wifi Deauth Evil Twin

<div align="center">
    <img src="https://github.com/Coderxrohan/Wifi-Deauth-Evil-Twin/blob/main/Images/ESP8266%20Node%20MCU.png" width="250" height="250 " alt="Project Logo">
</div>


A **Wifi Deauth Evil Twin**-inspired open-source project for seamless and efficient phishing detection. This repository aims to provide a powerful yet user-friendly framework for improving cybersecurity resilience.

---

## 🚀 Features

- **Real-time Phishing Detection**: Analyzes URLs and flags potential phishing attempts.
- **Advanced Machine Learning Models**: Integrated with state-of-the-art ML algorithms.
- **Cross-Platform Compatibility**: Supports Windows, macOS, and Linux.
- **Customizable Pipeline**: Easily adaptable to different use cases.
- **Comprehensive Logging**: Keeps detailed logs for debugging and auditing.
- **Interactive API**: RESTful endpoints for seamless integration.

---

## 🛠️ Technologies Used

- **Programming Language**: C++
- **Compiler Used**: Aurdino IDE 2.3.4
  

---

## 🛠️ Chipset's Used

- **Board / Chipset**: [Generic ESP8266 Nodemcu Esp8266](https://amzn.in/d/dZRqXoX)
- **Data Cable**: [Amazon basics Type A to Micro USB Braided Cable](https://amzn.in/d/gYF2WOa)
- **Adaptor**: [Portronics Fast Wall Charger](https://amzn.in/d/jdseyjr)
---

## 📂 Directory Structure

```
PhiSiFi/
├── src/              # Main source code
├── data/             # Dataset for training & testing
├── docs/             # Documentation and guides
├── tests/            # Unit and integration tests
├── notebooks/        # Jupyter notebooks for experimentation
├── scripts/          # Automation and helper scripts
├── config/           # Configuration files
└── README.md         # Project documentation (this file)
```

---

## 💻 Installation

### Prerequisites

1. Install [Aurdino IDE 2.3.4+ ](https://www.arduino.cc/en/software)
2. Install [CP210x USB to UART Bridge VCP Drivers](https://www.silabs.com/developer-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads)

### Steps
#### Downloading File
1) Install Arduino IDE.
2) In Aurdino go to ```File``` -> ```Preference```s add below URL to ```Additional Boards Manager URLs``` -> ```https://raw.githubusercontent.com/SpacehuhnTech/arduino/main/package_spacehuhn_index.json```
3) In Arduino go to ```Tools```  -> ```Board``` -> ```Boards Manager``` search for and install the ```deauther package```
4) Download the file [Wifi Deauth Evil Twin](https://github.com/Coderxrohan/Wifi-Deauth-Evil-Twin/blob/main/ESP8266_Wifi_Deauth_Evil_Twin.ino)
5) Select and open this file with Arduino IDE.
6) Select an ESP8266 Deauther board in Arduino under ```tools``` -> ```board```.
7) Connect your device and select the serial port in Arduino under ```tools``` -> ```port```
8) Click the Upload button

---
### How to use:
1) Connect to the Wifi named ```White Rawen``` with password ```Pass1290@``` from your phone/PC.
   
2) Select the target Wi-Fi name you want to attack (the list of available Wi-Fi devices refreshes every 30 seconds by default, but a page reload is required).
   
4) Click the Start Deauthing button to start kicking devices off the selected network. This will jam the target's Wi-Fi, and the user will be disconnected from Wi-Fi.
   
6) Click the Start Evil-Twin button. This will create a fake target's Wifi and make a portal to collect the password from the user. If the wrong password is entered, then nothing will happen. If the correct password is entered, then the portal will be closed, and the user's fake Wifi clone will be shut down. The original wifi ```White Rawen``` will come online again.

7) Connect to ```White Rawen``` to see the collected password.
   
8) You can stop any of the attacks by visiting 192.168.4.1/admin while connected to Evil-Twin AP or by resetting the ESP8266.
  
9) Note: If you power off or reset the chipset, the collected password data will be lost permanently.

---

## 🛡️ Security

This project follows security best practices to ensure minimal vulnerabilities.


---

## 📷 Screenshots

![Screenshot 1](https://github.com/Coderxrohan/Wifi-Deauth-Evil-Twin/blob/main/Images/Screenshot%20(1).png)
![Screenshot 2](https://github.com/Coderxrohan/Wifi-Deauth-Evil-Twin/blob/main/Images/Screenshot%20(2).png)

---

## 🤝 Contribution Guidelines

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit changes (`git commit -m "Added feature"`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request.

For detailed instructions, check out our [CONTRIBUTING.md](docs/CONTRIBUTING.md).

---

### Acknowledgements

- Thanks to the [PhiSiFi](https://github.com/p3tr0s/PhiSiFi) project for inspiration.
- Gratitude to the open-source community for their tools and contributions.

---

## 🌐 Connect With Us

- **GitHub**: [Coderxrohan](https://github.com/YourUsername)
- **Email**: [Mail Me](coderxrohan@gmail.com)
- **LinkedIn**: [Rohan Satkar](https://www.linkedin.com/in/rohansatkar)

---
## Credits:

- https://github.com/p3tr0s/PhiSiFi
- https://github.com/SpacehuhnTech/esp8266_deauther
- https://github.com/M1z23R/ESP8266-EvilTwin

---
## 📄 License

This project is licensed under the [MIT License](LICENSE).
