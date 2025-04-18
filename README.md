# 📶 QoS Classification in 5G Networks using Machine Learning

This repository contains the LaTeX report and documentation for a project focused on Quality of Service (QoS) classification in 5G networks using machine learning. The project explores how reinforcement learning and deep learning techniques can dynamically manage and classify QoS flows, contributing to more intelligent and adaptive 5G communication.

---

## 📘 Overview

As 5G evolves to support a wide range of services—such as URLLC, eMBB, and mMTC—precise and efficient Quality of Service (QoS) classification becomes essential. This project presents and compares multiple machine learning models, particularly Proximal Policy Optimization (PPO) and deep neural networks, for classifying and managing QoS flows based on real-time network parameters.

---

## 🔍 System Components

- **QoS Parameters**: Includes latency, bandwidth, reliability, jitter, and packet loss—core indicators for service quality in 5G.

- **Reinforcement Learning (RL)**:
  - Uses PPO for adaptive, policy-based control in dynamic 5G environments.
  - Learns from network conditions and improves resource allocation through feedback.

- **Deep Learning (DL)**:
  - Employs CNNs and RNNs to recognize traffic patterns and detect anomalies.
  - Enhances prediction accuracy using high-dimensional signal features.

- **Hybrid Models**:
  - Future-ready architectures combining RL and DL to boost adaptability and precision in QoS classification.

---

## 📊 Model Insights

| Technique     | Strengths                        | Challenges              |
|---------------|----------------------------------|--------------------------|
| PPO (RL)      | Adaptive, real-time decision-making | Requires training time   |
| CNN/RNN (DL)  | High pattern recognition accuracy | Needs large labeled datasets |
| Hybrid (DRL)  | Robust, scalable                 | Complex deployment       |

---

## 🔮 Future Work

- Integration of hybrid Deep Reinforcement Learning (DRL) models.
- Real-time deployment on edge devices.
- Continuous learning via online training to handle non-stationary environments.

---

## 📚 References

- Mahmood, A., Alasmary, W., & Khan, A. (2023). A survey on QoS classification using machine learning in 5G networks, *International Journal of Computer Science*.
- PPO Algorithm: Schulman et al., *Proximal Policy Optimization Algorithms*.
- CNN/RNN: General deep learning applications in networking.
