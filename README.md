# Mobile Processor Carbon Footprint

## Beyond the Surface: The Necessity of Detailed Metrics in Corporate Sustainability (IGSC'24)

The smartphone industry’s push for smaller, energy-efficient devices with advanced features often overlooks environmental impacts. Corporate sustainability reports provide broad overviews, masking critical details, especially about carbon footprints (CFP) of components like processors. This paper examines the gap between reported CFP trends and the rising CFP contributions of processors, highlighting deficiencies in reporting practices. We propose specific metrics to improve transparency and guide chip design and manufacturing toward sustainable solutions.

 <img src="images/Sustainability-MobileProcessor-Trend.jpg" alt="drawing" width="600"/> 

## Table of Contents

-   [Directory structure](#directory-structure)
-   [Main objective](#objectives)
-   [Key parameters](#key-parameters)
-   [Running GreenFPGA](#running-greenfpga)
-   [Outputs](#outputs)

## Directory Structure 

- **src/**
  - [ECO_chip.py](./src/ECO_chip.py) [Modified version of original ECO_chip.py to help with Mobile processor metric work] 
- **data**
  - [Apple-iPhone-Series.xlsx](./data/Apple-iPhone-Series.xlsx)
  - [Goole-Pixel-Series.xlsx](./data/Google-Pixel-Series.xlsx)
- [README.md](README.md)
- **images**
  - [Mobile-Sustainability-LCA.png](./images/Mobile-Sustainability-LCA.png)
  - [Sustainability-MobileProcessor-Trend.jpg](./images/Sustainability-MobileProcessor-Trend.jpg)


Two main objectives of this work are : 
1. 

Google processor data
Apple processor data

Add the two tables for that. Add references to Goolge and Apple sustainability reports. Then in the src directly add a top-level script that call ECO-CHIP. 

Add ECO-CHIP as a submodule in this repository.
