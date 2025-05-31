# sama7g54-ek-audio-ml
The primary goal of this project is to develop a real-time monitoring system that continuously assesses the operational health of a machine using audio data. By leveraging Mel-filter bank Energy (MFE) features, the system extracts critical frequency characteristics that correlate with various machine states. These features are then used to train a neural network capable of accurately classifying the machine’s condition into categories such as "good," "broken fault," and "heavy load motor."

To streamline development, the Edge Impulse platform is utilized for data collection, feature extraction, model training, and deployment. The final model is deployed on an embedded Linux device—the SAMA7G54 Evaluation Kit—demonstrating robust, real-time classification with high accuracy.





# Enhancing Predictive Maintenance with Audio Signal Processing and AI/ML

Traditional PdM methods—such as vibration sensors, current probes, and temperature monitoring—are often intrusive, expensive, and may miss subtle faults that don’t significantly impact power consumption or create noticeable vibrations. In demanding environments like factories and automotive systems, this can result in major failures and production stoppages. To address these limitations, this project demonstrates the integration of audio signal processing with AI/ML techniques into traditional PdM systems, creating a more robust monitoring solution. MEMS microphones—non-intrusive and cost-effective—are used for continuous audio monitoring, capturing early mechanical anomalies that other sensors often miss.
