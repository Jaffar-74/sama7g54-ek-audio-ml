# sama7g54-ek-audio-ml

Audio-based machine learning applications have emerged as powerful tools across various industries enabling everything from voice assistants and speech recognition to predictive maintenance in industrial systems. By analyzing audio signals, machine learning applications can uncover hidden patterns and insights across a range of scenarios from environmental sound monitoring to industrial health diagnostics offering a non-intrusive and cost-effective means of assessing system performance and detecting anomalies.

This project demonstrates such an audio ML application in the context of machine health monitoring. Using Mel-filter bank Energy (MFE) features, it captures key frequency characteristics of machine audio data. A neural network then classifies the machine’s condition into categories such as "good," "broken fault," and "heavy load motor." The system’s capabilities are showcased through deployment on an embedded Linux device (SAMA7G54 Evaluation Kit), achieving robust and real-time classification with high accuracy.

![Set-up](docs/pics/Hardware%20Setup%20SAMA7G54.png)

# Reference Documentation

- _[SAMA7G54-EK User's Guide](https://www.microchip.com/DS50003273)_
- _[Getting Started with the SAMA7G54-EK Audio System under Linux™](https://www.microchip.com/90003372)_
- _[Getting started with Edge Impulse](https://docs.edgeimpulse.com/docs)_

# Hardware Prerequisites

- [SAMA7G54 Evaluation Kit](https://www.microchip.com/en-us/development-tool/ev21h18a)
- Linux PC
- FTDI Cable
- Ethernet Cable
- USB Type-B Cable
- SD Card

# Software Prerequisites

- [Edge Impulse](https://edgeimpulse.com/)
- [Docker](https://www.docker.com/)
- [Node.js](https://nodejs.org/en)

# SAMA7G54 Evaluation Kit Overview

The SAMA7G54 Evaluation Kit [EV21H18A](https://www.microchip.com/en-us/development-tool/ev21h18a) provides a versatile Total System Solution platform that
highlights Microchip MPU and connectivity ICs.
The board features on-board memories, two Ethernet interfaces, three USB ports, two CAN
interfaces, one SD card connector, two mikroBUS™ click interface headers to support over 450
MikroElektronika Click boards™, an RPi CSI camera to support a camera module, an RPi extension
connector to support several extension boards, and provision to solder a Microchip ATWILC3000-
MR110xA Wi-Fi/Bluetooth module.

**Note:** RPi stands for “Raspberry Pi”. Raspberry Pi is a trademark of Raspberry Pi Trading.

# Enhancing Predictive Maintenance with Audio Signal Processing and AI/ML

Traditional PdM methods such as vibration sensors, current probes, and temperature monitoring are often intrusive, expensive, and may miss subtle faults that don’t significantly impact power consumption or create noticeable vibrations. In demanding environments like factories and automotive systems, this can result in major failures and production stoppages. To address these limitations, this project demonstrates the audio signal processing with AI/ML techniques to integrate into traditional PdM systems, creating a more robust monitoring solution. MEMS microphones non-intrusive and cost-effective are used for continuous audio monitoring, capturing early mechanical anomalies that other sensors often miss.
