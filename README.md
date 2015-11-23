# 2016mwc-award
The page for MWC award 6c: Best Technology Enabler.

# Experiment

This experiment will show the perofmance improvement by Skymizer on different benchmarks and hardware platforms. The detailed information of benchmarks and platforms used in experiment are shown in Table 1 and Table 2. In these experiment, all of the benchmarks on different platforms are compiled by Linaro GCC 4.9.3. 

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

For performance comparison, we use "-Ofast" compile flag as our performance baseline on each benchmarks and platforms. All reported performance results are normalized
to the baseline.
