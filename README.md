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
Internet-of-things (IoTs) deploy massive number of sensors to monitor the sys-tem and environment. Anomaly detection on sensor data is an important task for IoT maintenance and operation. In real applications, the occurrence of a system-level incident usually involves hundreds of abnormal sensors, making it imprac-tical for manual verification. The users require an efficient and effective tool to conduct incident analysis and provide critical information such as: (1) identify-ing the parts that suffered most damages and (2) finding out the ones that cause the incident. Unfortunately, existing methods are inadequate to fulfill these re-quirements because of the complex sensor relationship and latent anomaly in-fluences in IoTs. To bridge the gap, we design and develop a Temporal Graph based Incident Analysis System (TGIAS) to help users' diagnosis and reaction on reported anomalies. TGIAS trains a temporal graph to represent the anomaly relationship and computes severity ranking and causality score for each sensor. TGIAS provides the list of top k serious sensors and root-causes as output and illustrates the evidences on a graphical view. The system does not need any in-cident data for training and delivers high accurate analysis results in online time. TGIAS is equipped with a user-friendly interface, making it an effective tool for a broad range of IoTs.

## TGIAS Demo for ECML PKDD 2023:
[![Video](https://github.com/pengyuan0106/Temporal-Graph-based-Incident-Analysis-Tool-for-IoT/blob/main/frame.jpg)](https://youtu.be/V6AeiqG9OXY)
