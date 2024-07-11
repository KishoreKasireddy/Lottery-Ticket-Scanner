# Lottery Ticket Scanner

A project to scan and verify lottery tickets using an ESP module and a barcode reader.

## Table of Contents
- [Introduction](#introduction)
- [Components](#components)
- [Setup](#setup)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Contributing](#contributing)
- [License](#license)
-  [Contact](#Contact)

## Introduction

This project uses an ESP module and a barcode reader to scan lottery tickets. The scanned data is then processed to verify the ticket.

## Components

- ESP Module
- GM65 Barcode Reader

## Setup

1. **Connect Hardware**:
   - Connect the GM65 barcode reader to the ESP module as per the provided user manual.
   - Ensure proper power supply and connections.

2. **Install Software**:
   - Install the Arduino IDE.
   - Install necessary libraries for ESP and barcode reader.

3. **Upload Code**:
   - Open `BarCode.ino` in the Arduino IDE and upload it to the ESP module.
   - Open `ESP.ino` in the Arduino IDE and upload it to the ESP module.

## Usage

1. **Power the ESP Module**: Ensure the ESP module is powered on.
2. **Scan Ticket**: Use the barcode reader to scan the lottery ticket.
3. **Verify Ticket**: The ESP module processes the scanned data and verifies the ticket.

## Code Overview

### BarCode.ino
Usage:
Ensure the barcode scanner is correctly connected:
GM65 TX -> ESP8266 RX (GPIO4)
GM65 RX -> ESP8266 TX (GPIO5)
GM65 VCC -> ESP8266 3.3V
GM65 GND -> ESP8266 GND


# Contact
   Connections and Layouts are hidden.
   This is an ongoing Project
For more details. 
Contact - kishorekasireddi4@gmail.com 
