# sama7g54-ek-audio-ml

Audio-based machine learning applications have emerged as powerful tools across various industries enabling everything from voice assistants and speech recognition to predictive maintenance in industrial systems. By analyzing audio signals, machine learning applications can uncover hidden patterns and insights across a range of scenarios from environmental sound monitoring to industrial health diagnostics offering a non-intrusive and cost-effective means of assessing system performance and detecting anomalies.

This project demonstrates such an audio ML application in the context of machine health monitoring. Using Mel-filter bank Energy (MFE) features, it captures key frequency characteristics of machine audio data. A neural network then classifies the machine’s condition into categories such as "good," "broken fault," and "heavy load motor." The system’s capabilities are showcased through deployment on an embedded Linux device (SAMA7G54 Evaluation Kit), achieving robust and real-time classification with high accuracy.

![Set-up](docs/pics/Hardware%20Setup%20SAMA7G54.png)

# Enhancing Predictive Maintenance with Audio Signal Processing and AI/ML

Traditional PdM methods such as vibration sensors, current probes, and temperature monitoring are often intrusive, expensive, and may miss subtle faults that don’t significantly impact power consumption or create noticeable vibrations. In demanding environments like factories and automotive systems, this can result in major failures and production stoppages. To address these limitations, this project demonstrates the audio signal processing with AI/ML techniques to integrate into traditional PdM systems, creating a more robust monitoring solution. MEMS microphones non-intrusive and cost-effective are used for continuous audio monitoring, capturing early mechanical anomalies that other sensors often miss.
