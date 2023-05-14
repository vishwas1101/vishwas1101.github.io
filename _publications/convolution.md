---
title: "Convolution using RISC-V Processing Elements"
collection: publications
permalink: /publications/convolution
excerpt: 'Parallel execution of convolution algorithm to test a RISC-V based NoC'
date: Sep 2021 - Jan 2022
venue:
---

**Abstract:**
Convolution image filtering technique has been extensively used in image processing applications for sharpening the image, detecting the edges, blurring the image, noise removal etc. Optimization of the convolution algorithm for execution speed has become crucial as the size of the image increases. Loop unrolling is an optimization technique that is adopted for reducing the execution time of the algorithm by reducing the overheads caused by the loops in the algorithm implementation. RISC-V ISA based processing elements being open source are widely used in academia and industry. Hence, in this paper, we have attempted to implement convolution algorithm sequentially and with loop unrolling technique on a custom-developed RISC-V soft core processor. Further, to enhance the speed of operation, a multiprocessor framework has also been developed with Network-on-Chip based inter-core communication platform. The implemented algorithms are tested with RARS tool at assembly level and with Vivado tool at the architectural level. The architecture is also synthesized and implemented on Kintex FPGA evaluation platform. With the optimization techniques applied, a considerable improvement is observed in the number of branch instructions for loop operations and thereby the execution speed of the algorithm.