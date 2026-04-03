---
layout: default
title: High-Resolution Estimation of Mountain Glacier Velocity Based on Optical and Radar Remote Sensing
---

# High-Resolution Estimation of Glacier Velocity in the Muztagh Peak Region of the Eastern Kunlun Mountains Using Sentinel-1 and Sentinel-2 Imagery

As the “Asian Water Tower”, mountain glaciers on the Tibetan Plateau play a crucial role in freshwater supply across East Asia, Southeast Asia, and South Asia. Glacier flow velocity is a key indicator of their dynamic changes. Due to limitations in observational accuracy, previous studies have primarily focused on high-velocity regions (e.g., with annual velocities exceeding 100 m/year), while relatively little attention has been given to low-velocity glaciers, which constitute the majority on the Tibetan Plateau. This gap has limited a comprehensive assessment of glacier changes in the region.

In this project, we propose a multi-source remote sensing framework that integrates Sentinel-1 radar data and Sentinel-2 optical imagery. By optimizing several processing steps—including phase filtering, phase unwrapping, offset tracking, and time-series analysis—we achieve glacier velocity measurements with a spatial resolution of 50 meters and a temporal resolution of 30 days. The Muztagh Peak region in the Eastern Kunlun Mountains is used as a test site to analyze glacier velocity variations from January 2020 to December 2025.

![Mean Glacier Velocity in 2025](/assets/images/glacier_velocity/velocity_en.png)

The results show significant spatial variability in glacier flow velocity, ranging from a few meters per year to over 2,000 meters per year. Some glaciers exhibit surge behavior, characterized by rapid acceleration over a few months, with velocities increasing to several hundred or even thousands of meters per year. This study provides the first confirmed observation of glacier surging in this region. Compared with the benchmark NASA ITS_LIVE dataset, our velocity results show better consistency with glacier topography, reducing flow direction errors by approximately 30%. Furthermore, our results capture glacier acceleration at the scale of ~1 m/year² and seasonal velocity variations on the order of ~5 m/year, demonstrating the high precision of the proposed method.

![Time Series Example](/assets/images/glacier_velocity/time_series.png)