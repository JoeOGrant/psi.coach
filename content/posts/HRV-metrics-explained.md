---
title: "HRV Metrics"
date: 2023-03-01T21:40:28+01:00
draft: false
---



## time-domain

**interbeat interval (IBI) -** time period between successive heartbeats

**time-domain *indices –*** quantifications of the variability in *interbeat interval* measurements by discrete *time buckets*
>values may be expressed in original units or as the natural logarithm (Ln) of original units to achieve a more normal distribution

### time buckets

* **short-term (ST)** – about 5 minutes

* **ultra-short-term (UST)** – under 5 minutes
    >ST and UST values are NOT interchangeable with 24h values 

* **24 h** – a full day
    >Relevant to processes with slower fluctuations such as *circadian rhythms* and the *cardiovascular* system’s response to a wider range of external stimuli, routines and workloads.

### time-domain measures

| Parameter|Unit|Description|
|-|-|-|
|SDNN|ms|Standard deviation of NN intervals |
|SDRR|ms|Standard deviation of RR intervals|
|SDANN|ms|Standard deviation of the average NN intervals for each 5 min segment of a 24 h HRV recording |
|SDNN index (SDNNI)|ms|Mean of the standard deviations of all the NN intervals for each 5 min segment of a 24 h HRV recording|
|pNN50|%|Percentage of successive RR intervals that differ by > 50ms|
|HR Max - HR min|bpm|Average difference between the highest and lowest heart rates during each respiratory cycle|
|RMSSD|ms|Root mean square of successive RR interval differences|
|HRV triangular index | | Integral of interval histogram density divided by its height|
|TINN|ms|Baseline width of the RR interval histogram|

## frequency-domain
>In a novel and comprehensive peer-reviewed journal on the statistical methods and measurements of HRV, *The Task Force of the European Society of Cardiology and the North American Society of Pacing and Electrophysiology* divided heart rate (HR) oscillations into four bands.

**frequency-domain** ***measurements*** – estimates of the distribution of absolute or relative power into the following discrete frequency bands:

### frequency bands

* **ultra-low-frequency (ULF)** – ≤0.003 Hz

* **very-low-frequency (VLF)** – 0.0033–0.04 Hz

* **low-frequency (LF)** – 0.04 Hz–0.15 Hz

* **high-frequency (HF)** – 0.15 Hz–0.4 Hz

### frequency-domain measures

| Parameter|Unit|Description|
|-|-|-|
|ULF power|ms$^2$|Absolute power of the ultra-low-frequency band (≤0.003 Hz)|
|VLF power|ms$^2$|Absolute power of the very-low-frequency band (0.0033–0.04 Hz)|
|LF peak|Hz|Peak Frequency of the low-frequency band (0.04 Hz–0.15 Hz)|
|LF power|ms$^2$|Absolute power of the low-frequency band (0.04 Hz–0.15 Hz)|
|LF power|nu|Relative power of the low-frequency band in normal units|
|LF power|%|Relative power of the low-frequency band (0.04 Hz–0.15 Hz)|
|HF peak|Hz|Peak frequency of the high-frequency band (0.15 Hz–0.4 Hz)|
|HF power|ms$^2$|Absolute power of the high-frequency band (0.15 Hz–0.4 Hz)|
|HF power|nu|Relative power of the high-frequency band in normal units|
|HF power|%|Relative power of the high-frequency band (0.15 Hz–0.4 Hz)|
|LF/HF|%|Ratio of LF-to-HF power|


## sources

**https://www.frontiersin.org/articles/10.3389/fpubh.2017.00258/full**