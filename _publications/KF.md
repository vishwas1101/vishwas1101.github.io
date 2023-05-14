---
title: "Kalman Filter Applications in Microgrids"
collection: publications
permalink: /publications/KF
excerpt: Worked on Kalman Filter techniques for stability issues and state estimation of voltages to avoid voltage regulation issues in multiple Distributed Energy Resources.
date: Dec 2020 - Dec 2021
venue:
---

**Abstract:**
Several controllers address Load Frequency Control (LFC) to minimize deviations in system frequency caused due to rapid disturbances in load demand and RES penetration. However, large power systems' complexity and the significant frequency deviations observed often limit these controllers. In order to address these issues, a novel Cubature Kalman filter (CKF) and Extended Kalman filter (EKF) and Linear Quadratic Regulator (LQR) based on combined state estimation and optimal control is proposed. LQR is an optimal controller that curbs the frequency deviations by calculating optimal feedback gain values. The CKF (or EKF) is a novel state estimator algorithm used to estimate the state variables by minimizing the error between actual and estimated states. The proposed control is tested on a small single-area power system and a large-scale power system based in Egypt. The results obtained are compared with the existing Extended Kalman filter (EKF) and LQR-based control, Virtual Synchronous Generator (VSG) based control, and conventional Proportional-Integral-Derivative (PID) control with over and under frequency protection circuit. The efficacy of CKF-LQR and EKF-LQR is emphasized through the analysis of various simulation cases of the power system. The findings suggested that the proposed controller’s performance was robust under frequency measurement noise, low inertia, sudden renewable energy source (RES) and load switching. The outcome shows that the proposed control is robust and can effectively regulate the system frequency compared to the other controllers.

Two papers have resulted from this work. EKF-LQR paper is published in the *2nd International Conference Power Electronics & IoT Applications in Renewable Energy* and its Control (PARC) - [link](https://ieeexplore.ieee.org/abstract/document/9726570). The other paper is currently under review in a Q1 journal *Electric Power Systems Research*. 

The code and the other details regarding the course can be found in this [repository](https://github.com/vishwas1101/KF-in-microgrids). The code is the trivial proof of concept. The other codes related to EKF-LQR and CKF-LQR on different power systems are not yet public. 




