---
title: "DownScaleBench for developing and applying a deep learning based urban climate downscaling"
date: 2023-08-01T12:15:12.915Z
draft: false
featured: false
tags:
  - Urban
  - ML
  - Downscaling
categories:
  - Urban
  - ML
  - Downscaling
image:
  filename: downscale_bench.webp
  focal_point: Smart
  preview_only: false
---
Cities need climate information to develop resilient infrastructure and for adaptation decisions. The information desired is at the order of magnitudes finer scales relative to what is typically available from climate analysis and future projections. Urban downscaling refers to developing such climate information at the city (order of 1 – 10 km) and neighborhood (order of 0.1 – 1 km) resolutions from coarser climate products. Developing these higher resolution (finer grid spacing) data needed for assessments typically covering multiyear climatology of past data and future projections is complex and computationally expensive for traditional physics-based dynamical models. In this study, we develop and adopt a novel approach for urban downscaling by generating a general-purpose operator using deep learning. This ‘DownScaleBench’ tool can aid the process of downscaling to any location. The DownScaleBench has been generalized for both in situ (ground- based) and satellite or reanalysis gridded data. The algorithm employs an iterative super-resolution convolutional neural network (Iterative SRCNN) over the city. We apply this for the development of a high-resolution gridded precipitation product (300 m) from a relatively coarse (10 km) satellite-based product (JAXA GsMAP). The high-resolution gridded precipitation datasets is compared against insitu observations for past heavy rain events over Austin, Texas, and shows marked improvement relative to the coarser datasets relative to cubic interpolation as a baseline. The creation of this Downscaling Bench has implications for generating high-resolution gridded urban meteorological datasets and aiding the planning process for climate-ready cities.



Singh, M., Acharya, N., Jamshidi, S. et al. DownScaleBench for developing and applying a deep learning based urban climate downscaling- first results for high-resolution urban precipitation climatology over Austin, Texas. Comput.Urban Sci. 3, 22 (2023). 
[https://doi.org/10.1007/s43762-023-00096-9](https://doi.org/10.1007/s43762-023-00096-9 "Persistent link using digital object identifier")