# FPGACompressor

## Overview

This project implements a high-performance pipeline for real-time lossless compression of data streamed to an FPGA via Ethernet. The system leverages NEON SIMD instructions and out-of-order queue processing to accelerate computation, resulting in significant performance improvements. The code [repo](https://github.com/manvi27/Deduplication-and-Compression) is private, reach out to me at manviaga27@gmail.com to gain access to the repo. <o>

### Key features:
- Real-time lossless compression on Ethernet-streamed data to FPGA
- Accelerated computation using NEON SIMD and out-of-order queue
- OpenCL implementation for concurrent processing
- 50% improvement in pipeline throughput
- 10x optimization of BRAM utilization in FPGA using Associative mapping

Architecture
The system architecture consists of the following components:

- Ethernet Data Ingestion
- NEON SIMD Acceleration
- Out-of-Order Queue for Concurrent Processing
- OpenCL Implementation on FPGA
- Associative Mapping for BRAM Optimization

For more details, refer to the [document](https://drive.google.com/file/d/1sCXrdsLPDJEZZdovsNQsBu8r12goxcXN/view?usp=sharing) 