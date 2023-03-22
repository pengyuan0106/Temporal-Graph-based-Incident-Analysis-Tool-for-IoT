<h1 align="center">Temporal Graph based Incident Analysis Tool for Internet of Things</h1>
<p align="center">
Peng Yuan<sup>1</sup>, Lu-An Tang<sup>1</sup>, Haifeng Chen<sup>1</sup>,David S Chang<sup>2</sup>, Moto Sato<sup>1</sup>, and Kevin Woodward<sup>2</sup>
</p>

<p align="center">
<sup>1</sup> NEC Labs America, Princeton, NJ, USA
</p>
<p align="center">
<sup>2</sup> Lockheed Martin Space, Denver, CO, USA
</p>
       
           
## Abstract
Internet-of-thing (IoT) applications deploy massive number of sensors to moni-tor the system and environment. Anomaly detection on sensor data is an im-portant task for IoT maintenance and operation. However, the occurrence of a system-level incident may involve hundreds of sensors, thereby rendering man-ual verification impracticable for the end user. The end user requires an incident analysis that can answer critical questions such as: (1) identifying the most damaged system parts and (2) finding out the components that likely cause the incident. Nevertheless, most existing works are inadequate in addressing these requirements. To bridge the gap, we designed and developed a Temporal Graph based Incident Analysis System (TGIAS) to help the end user's diagnosis and decision-making on the monitored alerts in IoT. TGIAS trains a temporal graph for sensor relationship from historical data, conducts sensor severity ranking and causality analysis based on the graph. TGIAS can provide the information like top k serious sensors and top k root causes of the incident. The system has minimal parameter settings and delivers high accuracy on incident analysis re-sults. TGIAS can be deployed to process online alerts in IoT. It is equipped with a user-friendly interface, making it an efficient and effective tool for diag-nosing a broad range of IoT applications.

## TGIAS Demo for ECML PKDD 2023:
[![Video](https://github.com/pengyuan0106/eXplainable-Anomaly-Detection-System/blob/main/frame1.jpg)](https://youtu.be/e6WRtAps5cc)
