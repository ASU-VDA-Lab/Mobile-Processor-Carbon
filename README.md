# Mobile Processor Carbon Footprint Trend [[Slides](./uploads/IGSC-Chetan-2024.pdf)]

## Beyond the Surface: The Necessity of Detailed Metrics in Corporate Sustainability (IGSCC'24)

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

## Main Objectives
Two main objectives of this work are: 

### Objective 1: Call to action for industry to include detailed data in sustainability reports 
 <img src="images/Mobile-Sustainability-LCA.png" alt="drawing" width="600"/> 

### Call to action for the community to incorporate sustainability-oriented metrics for benchmarking
- #### Performance Sustainability Index (Perf-SI)
The performance sustainability index provides information about how much performance we get for every CO2eq. The key thing to note here is the total CFP considers the contribution of both embodied and operational CPF.
When comparing devices, performance alone is not sufficient. We must consider the device's area, power, sustainability impact, and performance. 

$\Large Perf - SI = \frac{Performance}{Total CO_2 eq.}$


- #### Workload-depended carbon footprint
There has been increased demand for computing in recent years, making evaluating workload-dependent CFP important. 

$\Large C_{workload} = T_{workload} \times P \times CI$

$T_{workload}$ - Time takne to run the workload  

$P$ - power of the processor 

$CI$ - Carbon intensity 

- #### Carbon footprint per billion transistor
CFP per billion transistors is another metric that can be used to see progress in semiconductor manufacturing. 

- #### Carbon footprint per GB
Companies need to include CFP per GB in their reports. 

## Dataset 
We have uploaded the entire Google Pixel series, and iPhone series processor specifications and sustainability-related carbon footprint details of both the processor and the entire phone under **data** directory [[1]][Apple-reports] [[2]][Google-reports]
### Apple Processor Data
- [Apple-iPhone-Series](./data/Apple-iPhone-Series.xlsx) contains details for iPhone series processors
### Google Processor Data
- [Google-Pixel-Series](./data/Google-Pixel-Series.xlsx) contains details for the Google Pixel series processors

## Citation

If you find our work **Mobile-Processor-Carbon** useful or relevant to your research, please kindly cite our paper:

```bibtex
@inproceedings{sudarshan2024igsc,
  author = {Chetan Choppali Sudarshan, Aman Arora, Vidya A. Chhabria},
  title = {Beyond the Surface: The Necessity of Detailed Metrics in Corporate Sustainability},
  booktitle={2024 IEEE 15th International Green and Sustainable Computing Conference (IGSC)},
  year={2024}
  location = {Austin, US},
  series = {IGSCC '24},
  pages = {145-150},
  doi = {10.1109/IGSC64514.2024.00035},
  url = {https://doi.ieeecomputersociety.org/10.1109/IGSC64514.2024.00035}
}

```

[Apple-reports]: <https://www.apple.com/environment/>
[Google-reports]: <https://sustainability.google/reports/>
