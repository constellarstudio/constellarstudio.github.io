---
layout: default
title: Crude Orbit Refinement Analysis for LuTan-1 Satellite Data
---

# Crude Orbit Refinement Analysis for LuTan-1 Satellite Data

Accurate satellite orbit data is typically a prerequisite for achieving interferometric processing. Although radar satellites utilize the Global Navigation Satellite System (GNSS) to record the satellite's position in real time during data acquisition, the orbit data obtained through this method—commonly referred to as crude orbit data—usually contains large errors and cannot meet the requirements of high-precision interferometric processing. Specifically, large orbital errors reduce the estimation accuracy of the spatial baseline, preventing the flat-earth phase and topographic phase in the raw interferogram from being completely removed. The residual flat-earth and topographic phases subsequently degrade the quality of downstream interferometric analyses, such as deformation monitoring and tomography.

To improve orbital accuracy, people usually combine precise processing products from external navigation satellites, complex celestial mechanics models, and smoothing filter algorithms to solve for precise orbit data. However, the computation of precise orbit data generally requires a long period of external data collection, resulting in a 2- to 3-week delay between its publication and the radar data acquisition time. This severely hinders the application of satellite radar data for the processing and analysis of sudden geological disasters, such as landslides and earthquakes.

To overcome this challenge, we have developed a method that utilizes the crude orbit data embedded within the radar data package for orbit refinement processing. Combined with the dynamic equations of satellite mechanics, an Extended Kalman Filter (EKF) is employed to perform smoothing on the three-dimensional position and velocity vectors of the radar satellite. Taking the data acquired by the LuTan-1 satellite on May 20, 2026, in Tanchang County, Gansu Province, China as an example, the figure below illustrates the differences between the three components of the satellite position vector before and after filtering. The horizontal axis represents time in seconds, and the vertical axis represents the difference in position components in kilometers. As can be seen from the figure, the orbital position difference of the LuTan-1 satellite before and after filtering varies within a range of tens of centimeters to 1.5 meters, indicating that the crude orbit data contains significant errors.

![Orbit Filtering Results](/assets/images/tanchang/orbit_residuals.png)

To verify the effectiveness of the orbit filtering, we performed interferometric processing using two images acquired by the LuTan-1 satellite in the same region on May 20, 2026, and July 7, 2026. The interferograms obtained using the original crude orbit data and the filter-corrected orbit data are shown in the figure below:

![Large-scale Amplitude Change Detection Map of Tehran](/assets/images/tanchang/interferogram_comparison_en.png)

It can be observed that the interferogram on the left, obtained using the crude orbit data, exhibits distinct dense fringes caused by orbital errors. In contrast, the orbit filtering effectively removes these cluttered interferometric fringes by smoothing the orbit, thereby validating the effectiveness of the orbit refinement processing approach used in our study.