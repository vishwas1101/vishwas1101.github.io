---
title: "Hardware Accelerators for NLP applications"
collection: publications
permalink: /publications/AxONAL
excerpt: Developed Hardware Accelerators for Transformer Encoders and BERT models to perform various Natural Language Processing tasks with focus on resource constrained devices.
date: June 2022 - Dec 2022
venue:
---

**Abstract:**
Hardware capable of efficiently running various Natural language processing (NLP) models and tasks has been a primary focus in the past few years. The major intention of this work is to develop an efficient hardware framework for BERT, ensuring minimal resource utilization. This would aid resource-constrained devices in running significantly large NLP tasks. The following three techniques are used: Initially, the memory occupied by the model parameters is reduced through Quantization. Later, a single matrix multiplier unit based on concatenation of weight matrices is developed on the PL. Lastly, approximate multiplier units are incorporated into the design to reduce resource utilization further. Using these techniques, a flexible software-hardware co-design framework is developed, allowing the user to choose the model precision, the different parameters in the matrix multiplication unit, the approximate/accurate multipliers, etc., based on their hardware requirements. The designs are then tested on the Avnet Ultra96v2 FPGA board using the PYNQ framework, resulting in a design that effectively runs on resource constrained devices.

