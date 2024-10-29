# Mobile Processor Carbon Footprint Trend

## Beyond the Surface: The Necessity of Detailed Metrics in Corporate Sustainability (IGSC'24)

The smartphone industry’s push for smaller, energy-efficient devices with advanced features often overlooks environmental impacts. Corporate sustainability reports provide broad overviews, masking critical details, especially about carbon footprints (CFP) of components like processors. This paper examines the gap between reported CFP trends and the rising CFP contributions of processors, highlighting deficiencies in reporting practices. We propose specific metrics to improve transparency and guide chip design and manufacturing toward sustainable solutions.

 <img src="images/Sustainability-MobileProcessor-Trend.jpg" alt="drawing" width="600"/> 

## Table of Contents

-   [Directory structure](#directory-structure)
-   [Main objective](#main-objectives)
-   [Dataset](#dataset)

## Directory Structure 

- **[ECO-CHIP](./ECO-CHIP/)** [Submodule to original ECO-CHIP]
- **src/**
  - [ECO_chip.py](./src/ECO_chip.py) [Modified version of original ECO_chip.py to help with Mobile processor metric work] 
- **data**
  - [Apple-iPhone-Series.xlsx](./data/Apple-iPhone-Series.xlsx)
  - [Goole-Pixel-Series.xlsx](./data/Google-Pixel-Series.xlsx)
- [README.md](README.md)
- **images**
  - [Mobile-Sustainability-LCA.png](./images/Mobile-Sustainability-LCA.png)
  - [Sustainability-MobileProcessor-Trend.jpg](./images/Sustainability-MobileProcessor-Trend.jpg)

## Main Objecives
Two main objectives of this work are : 
### Call to action for industry to include detailed data in sustainaiblity reports 
 <img src="images/Mobile-Sustainability-LCA.png" alt="drawing" width="600"/> 

### Call to action for the community to incorporate sustainaiblity-oriented metrics for benchmarking chips and architectures


## Dataset 
We have uploaded the entire Google Pixel series, and iPhone series processor specifications and sustainability related carbon footrpint details of both the processor and the entire phone under **data** directory [[1]][Apple-reports] [[2]][Google-reports]
### Apple Processor Data
- [Apple-iPhone-Series](./data/Apple-iPhone-Series.xlsx) contains details for iPhone series processors
### Google Processor Data
- [Google-Pixel-Series](./data/Google-Pixel-Series.xlsx) contains details for the Google Pixel series processors


Add the two tables for that. Add references to Goolge and Apple sustainability reports. Then in the src directly add a top-level script that call ECO-CHIP. 

[Apple-reports]: <https://www.apple.com/environment/>
[Google-reports]: <https://sustainability.google/reports/>