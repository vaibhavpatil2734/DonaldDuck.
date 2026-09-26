# 🦆 DonaldDuck in Action
<div align="center">

<img src="demo.gif" alt="DonaldDuck Demo" width="700">

</div>

⚠️ **Note:** The original ESP32 sketch used in the demo is **not included in this repository**.

---

## 📝 About

**DonaldDuck** is an **ESP32-based HID security research tool** inspired by the concept of a Rubber Ducky. It can emulate a keyboard and automate predefined keystrokes and commands for **authorized security testing, penetration-testing labs, and controlled environments**.

---

## 🔌 Hardware

**DonaldDuck** is built using an **ESP32** configured to operate as a HID keyboard.

The device can automatically send predefined keyboard input when connected to or paired with an authorized test system.

---

## 🚀 Features

* **ESP32 HID Keyboard**: Emulates keyboard input using an ESP32.
* **Automated Keystrokes**: Executes predefined keyboard sequences automatically.
* **Command Automation**: Automates authorized command-line operations.
* **Payload Automation**: Supports controlled security-testing workflows.
* **Bluetooth HID**: Communicates with compatible systems through Bluetooth HID.
* **Security Testing**: Useful for demonstrating endpoint-security controls.
* **Rapid Execution**: Executes predefined actions without manual keyboard input.
* **Custom Payloads**: Payload logic can be adapted for controlled testing environments.

---

## 🛠️ Technologies Used

* **Microcontroller**: ESP32
* **Programming**: Arduino / C++
* **HID**: Bluetooth HID Keyboard
* **Communication**: Bluetooth
* **Target Platform**: Windows
* **Development Tools**: Arduino IDE, Git, GitHub
* **Security Testing**: Command-line automation and controlled payload workflows

---

## 💻 Setup

### 1. Clone the repository

```bash
git clone https://github.com/vaibhavpatil2734/DonaldDuck.git
```

### 2. Open the Project

Open the Arduino project in **Arduino IDE**.

### 3. Configure ESP32

Install the required ESP32 board support and the HID/BLE keyboard library used by the project.

### 4. Upload

Select the appropriate ESP32 board and COM port, then upload the firmware.

### 5. Test

Use the device only with an **authorized test machine or isolated laboratory environment**.

---

## 🎯 Use Cases

DonaldDuck can be used for:

* HID security research
* Red-team and penetration-testing labs
* Endpoint-security demonstrations
* Security-awareness testing
* Automated Windows command testing
* Learning about HID-based attack techniques
* Testing defensive controls against unauthorized HID devices

---

## ⚠️ Ethical Use

DonaldDuck is intended for **authorized cybersecurity research and educational purposes**.

Do not use the device to deploy malware, RATs, steal credentials, capture information, or execute commands on systems without explicit authorization.

Always perform testing in an isolated lab or on systems where you have permission to conduct security testing.
