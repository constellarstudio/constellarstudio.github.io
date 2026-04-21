---
layout: default
title: InSAR Time-Series Analysis for Surface Deformation Monitoring in Open-Pit Mining Areas
---

# InSAR Time-Series Monitoring of Surface Deformation in Large Open-Pit Mines: A Case Study in the Rhenish Coalfield, Germany

Open-pit mining continuously alters surface structures, leading to subsidence, slope deformation, and localized instability. This case study focuses on three major open-pit lignite mines—Hambach, Garzweiler, and Inden—located in the Rhenish coalfield in western Germany. Multi-temporal Synthetic Aperture Radar (SAR) data are used to monitor and analyze surface deformation associated with mining activities.

The study area lies between Aachen and Cologne and represents one of the largest and most intensively exploited mining regions in Europe. Its continuous anthropogenic disturbance and large-scale deformation patterns make it an ideal case for demonstrating the application of InSAR in engineering monitoring.

---

## Methodology

This study employs the Small Baseline Subset (SBAS) InSAR technique to derive deformation velocity fields and time series from Sentinel-1 SAR data. The processing workflow includes co-registration, interferogram generation, topographic phase removal, phase unwrapping, and time-series inversion.

To mitigate atmospheric effects, a **common-point stacking** approach is applied to estimate the Atmospheric Phase Screen (APS). Compared to conventional planar fitting, this method better preserves large-scale, low-frequency deformation signals, which are critical in mining environments.

In addition, coherence-based pixel selection is used to improve inversion stability by filtering out low-quality observations and reducing noise propagation.

Ascending and descending orbit data are further combined to decompose line-of-sight (LOS) deformation into vertical and horizontal components, providing a more comprehensive characterization of ground movement.

---

## Deformation Results

![Surface deformation velocity map](/assets/images/german_mine/large.webp)

The results reveal strong spatial correlation between deformation patterns and mining activities:

- Backfilled areas exhibit significant subsidence (up to ~20–25 cm/yr)  
- Active excavation zones show uplift or positive LOS deformation (up to ~15 cm/yr)  
- Surrounding agricultural areas display minor subsidence, likely related to soil compaction  

The deformation field shows good spatial continuity and low noise levels, indicating reliable results.

---

## Time-Series Analysis

![Deformation time series](/assets/images/german_mine/timeseries.webp)

Time-series analysis at representative points indicates:

- Excavation zones show differences between ascending and descending results, suggesting significant horizontal motion  
- Backfilled areas exhibit consistent signals across both viewing geometries, indicating deformation dominated by vertical subsidence  

These differences reflect distinct deformation mechanisms associated with mining processes.

---

## 2D Deformation Decomposition

![2D deformation components](/assets/images/german_mine/small.webp)

By combining ascending and descending observations, LOS deformation is decomposed into vertical and horizontal components:

- **Vertical deformation** closely matches LOS patterns, with subsidence concentrated in backfilled areas  
- **Horizontal deformation** shows consistent movement toward the center of the pits along slopes  

Typical magnitudes include:

- Hambach: up to ~10 cm/yr horizontal motion  
- Garzweiler: over ~5 cm/yr  
- Inden: up to ~7 cm/yr  

Further analysis indicates that horizontal deformation is mainly concentrated in steeper slope sections (>25°), reflecting lateral material movement driven by gravity and excavation processes.

---

## Engineering Implications

This case demonstrates that InSAR time-series analysis can:

- Accurately identify subsidence centers and active mining zones  
- Capture slope movement and potential instability areas  
- Provide continuous deformation time series for trend analysis  
- Support risk assessment and long-term monitoring in mining environments  

Compared to traditional methods, InSAR offers wide-area coverage, cost efficiency, and consistent temporal observations, making it particularly suitable for continuously evolving engineering settings.

---

## Summary

By integrating SBAS-InSAR with multi-orbit observations, this study reconstructs two-dimensional deformation fields and significantly improves the interpretation of complex surface movements in mining areas.

The methodology is broadly applicable to engineering monitoring scenarios, including infrastructure stability assessment and geohazard analysis, demonstrating the value of spaceborne SAR in real-world applications.