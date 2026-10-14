# 1948 Pretoria Aerial Super-Upscaler & Mosaic Stitcher

A specialized, web-based photogrammetry and ortho-rectification toolkit designed for processing historical aerial survey plates (Job D147, January 1948). 

## Features
* **Auto-Calculated Photogrammetry:** Automatically derives flight height ($H$) and focal length ($f$) from plate dimensions and standard survey specs.
* **Inclinometer Homography Correction:** Calculates local perspective and tilt offsets ($dX, dY$) to correct raw historical survey angles.
* **Archival Resolution Booster:** High-quality multi-pass bicubic upsampling paired with faithful edge recovery unsharp masking.
* **Instrument Preservation:** Protects plate borders, flight clocks, altimeter dials, and "Jan 48" metadata tags during processing.
