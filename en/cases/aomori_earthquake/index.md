---
layout: default
title: Disentangling Earthquake Deformation from Multi-Orbit InSAR
---

# Disentangling Earthquake Deformation from Multi-Orbit InSAR Observations

For the Sentinel-1 satellite, accounting for its look geometry, when it tracks on a South-to-North orbit (ascending, looking East), the target exhibits a Line-of-Sight (LOS) displacement of approximately 9 cm away from the sensor. Conversely, when it tracks on a North-to-South orbit (descending, looking West), the target shows a LOS movement of approximately 7 cm toward the sensor.

Assuming the target lies at the center of the swath observed by both tracks, and that the North-South displacement is close to zero, the true 3D surface deformation can be solved through geometric decomposition. The results yield a vertical displacement of approximately 1.2 cm subsidence and an East-West displacement of approximately 14 cm toward the East.

This analysis demonstrates that the LOS signal is primarily dominated by the horizontal Eastward displacement, with vertical subsidence contributing only a small fraction. This also perfectly explains why the LOS signal amplitudes of the ascending and descending tracks are asymmetric (9 cm vs 7 cm) and have opposite signs: this is a typical signature of strong East-West horizontal deformation.

ALOS-2 and ALOS-4 observations indicated approximately 5 cm of subsidence and 9 cm of Eastward displacement. In this specific scenario, the ascending (South-to-North, looking East) LOS observation was proven to be more accurate. If we use the ALOS-derived deformation to perform a forward prediction, under the same assumptions that the target is in the swath center and North-South movement is zero, we get the predicted LOS deformation: ascending 9.1 cm, descending -0.9 cm.

This means that the ascending track is almost perfectly self-consistent with the "true deformation" in LOS space, while the descending track clearly "over-responded" to the signal. This highlights the critical importance of cross-calibrating multi-orbit InSAR datasets in complex horizontal deformation scenarios.

![Aomori Earthquake Deformation Decomposition](/assets/images/aomori_earthquake/aomorieq.webp)