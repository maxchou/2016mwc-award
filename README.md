# Experiment

This experiment will show the perofmance improvement by Skymizer on different benchmarks and hardware platforms. The detailed information of benchmarks and platforms used in experiment are shown in Table 1 and Table 2.

#### Table 1. Benchmark List

Benchmarks		| Description  
---------------	| ------------- 
Coremark		| Benchmark that aims to measure the performance of CPU used in embedded systems.
Dhrystone		| Benchmark that measures the integer performance of processors and compilers.
AutoBench (EEMBC)| A suite of benchmarks that allow users to predict the performance of microprocessors and microcontrollers in automotive, industrial, and general-purpose applications.
ConsumerBench (EEMBC) | A suite of benchmarks that allows the user to approximate the performance of processors in digital still cameras, printers, and other embedded systems that handle digital imaging tasks.
TeleBench (EEMBC) | A suite of benchmarks that allows the users to approximate the performance of processors in modem and related fixed-telecom applications.


#### Table 2. Platform List

Platform | CPU | Memory | OS  
---------|-----|--------|--- 
ODROID-U2|Samsung Exynos 4412 ARM Cortex-A9 Quad Core 1.7Ghz |2GB DDR2|Ubuntu 15.10
Nvidia Jetson TK1|Nvidia T124 ARM Cortex-A15 (4+1) Quad Core 2.32GHz|2GB DDR3|Ubuntu 14.04.1

For performance comparison, we use Linaro GCC compiler version 4.9.3 with "-Ofast" compile flag as our performance baseline on each benchmarks and platforms. We take the average of 100 runs as the final performance result for each benchmark on different platforms. All reported performance results are normalized to the baseline. 

Figure 1. shows the result of the performance improvement by Skymizer on different platforms. The results show that Skymizer can speed up Coremark XX%, Dhrystone XX%, AutoBench XX%, ConsumerBench XX%, and TeleBench XX% on ODROID-U2. On Nvidia Jetson TK1, Skymizer can speed up Coremark XX%, Dhrystone XX%, AutoBench XX%, ConsumerBench XX%, and TeleBench XX%.
