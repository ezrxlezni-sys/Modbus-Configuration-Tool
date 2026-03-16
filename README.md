# Modbus Configuration Tool

A Python-based Modbus Configuration Tool designed for **IRIV PiControl** and **IRIV IO Controller (IOC)**.  
This tool helps users **scan and identify the correct Modbus Slave ID and baudrate** of connected Modbus RTU devices.

It is useful when the communication parameters of a device are **unknown or misconfigured**, allowing engineers and students to quickly troubleshoot Modbus connections.

---

## Features

- Scan multiple **baudrates**
- Detect **Modbus Slave ID**
- Simple **Python-based implementation**
- Lightweight and easy to modify
- Designed for **IRIV PiControl and IO Controller**

---

## Project Structure

- **library/** – Contains the Modbus scanning functions.
- **main/** – Example program that runs the scanner.
- **README.md** – Project documentation.

---

## Requirements

- Python 3.x
- IRIV PiControl or IRIV IO Controller
- RS485 Modbus connection
- Basic understanding of Modbus RTU communication

---

## How It Works

The tool scans common Modbus baudrates and slave IDs.  
If a device responds to the request, the tool will display:

- Detected **Slave ID**
- Working **baudrate**

This allows users to quickly determine the correct communication parameters.

---

## Usage

1. Copy the library and main code to your device.
2. Open the `main.py` file.
3. Run the script.

Example output:

Testing Baudrate: 9600
Trying Slave ID: 1
No Response
Trying Slave ID: 2
FOUND device!
Baudrate: 9600
Slave ID: 2
Data: (543,)

---

## Applications

- Modbus troubleshooting
- Identifying unknown device settings
- Industrial automation testing
- Educational learning for Modbus communication

---

## Disclaimer

This project is provided for educational and demonstration purposes.  
Always follow proper safety procedures when working with industrial controllers and communication equipment.

---

## License

This project is released for educational use.
