# Getting Started with Edge Impulse

## Introduction

Edge Impulse is a powerful platform for developing machine learning models specifically for embedded and edge devices. It simplifies the process of collecting data, extracting meaningful features, training models, and deploying them directly to devices making it much easier to create real-time, intelligent applications at the edge.

With support for audio, vision, and sensor data, Edge Impulse empowers developers to build solutions that run directly on microcontrollers, embedded Linux devices, and other low-power hardware. The platform’s intuitive interface, robust APIs, and flexible deployment options make it a go-to choice for applications like predictive maintenance, environmental monitoring, industrial IoT, and much more.

## Steps

### 1️⃣ Setting Up Edge Impulse and Configuring the Target Device

1. Sign up for an Edge Impulse account by visiting [Edge Impulse Signup](https://edgeimpulse.com/signup).
2. After successfully logging in, locate the **+ Create new project** button on the home page. Click this button to initiate the project setup process.
3. Enter a project name and select either **Public** or **Private** for the project visibility. Click **Create new project** to complete the setup.
4. In the **Dashboard** menu, click the button in the top-right corner to add a target device. <br>![Target_Device](docs/pics/Target_Sel.jpg)
5. In the **Target device** drop-down menu, select **Microchip SAMA7G54 Evaluation Kit**.
6. Click the **Save** button to save the configuration.<br>
   <img src="docs/pics/Target_Config.png" alt="Target_Configuration" width="400" />

### 2️⃣ Data Collection for Model Training

1. The model requires a dataset for training, which can be sourced through various methods such as recordings, live capture, or online datasets. In this project, the dataset is sourced from the [Kaggle](https://www.kaggle.com/) platform.<br>

   <br>
   **About the Dataset📌:** The **IDMT-ISA-ELECTRIC-ENGINE** dataset contains audio files from three similar units of an electrical engine (2ACT Motor Brushless DC 42BLF01, 4000 RPM, 24VDC). These recordings simulate different acoustic conditions:

**Dataset Specifications:**

- **Sampling Rate:** 44.1 kHz
- **Resolution:** 32-bit
- **Audio Type:** Mono
- **States:** Good, Heavy Load, Broken
