<div align="center">

# SPATIAL & ARCHITECTURAL PROCESSING SUITE

**CLIENT-SIDE COMPUTATIONAL GEOMETRY & PHOTOGRAMMETRY**

[**[ LAUNCH LIVE SYSTEM ]**](https://satsujjinn.github.io/spatial-architectural-suite/)

---

### I. PROJECTIVE RECTIFICATION PLATE ("MORGENSTER" ELEVATION)

<img src="assets/demo_blueprint.jpg" width="100%" alt="Rectified Blueprint">

---

### II. TELEMETRY & CONTROL MATRICES

| 01. 4-POINT HOMOGRAPHY | 02. MONOCHROME THRESHOLD |
| :---: | :---: |
| <img src="assets/demo_corners.jpg" width="100%" alt="Corner Pins"> | <img src="assets/demo_monochrome.jpg" width="100%" alt="Monochrome Output"> |
| **03. 16X BICUBIC SUPER-SAMPLING** | **04. L1 ZERO-DIFFERENCE REGISTRATION** |
| <img src="assets/demo_upscaler.jpg" width="100%" alt="Universal Upscaler"> | <img src="assets/demo_stitcher.jpg" width="100%" alt="Mosaic Stitcher"> |

---

### III. ARCHITECTURAL & MATHEMATICAL SPECIFICATIONS

| MODULE | SOURCE FILE | MATHEMATICAL FORMULATION |
| :---: | :---: | :---: |
| **PERSPECTIVE DE-SKEW** | `000_Architectural_Perspective_App.html` | 8-DOF Projective Homography via `Float64Array` Gaussian Elimination & Bilinear Interpolation |
| **SCALE MODEL STUDIO** | `000_Architectural_Scale_Model_App.html` | Metric-to-Scale Conversion, Kerf/Butt-Joint Deduction, Secant Slope & 2-Pin Calibration |
| **AERIAL ORTHO-RECTIFIER** | `000_Aerial_Super_Upscaler_App.html` | Optical Altitude Scaling ($H = f \cdot S$) & Inclinometer Centroid Homography |
| **UNIVERSAL RESAMPLER** | `000_Universal_Photo_Upscaler_App.html` | Single-Pass Dynamic Range Normalization & 5-Point Laplacian Unsharp Masking |
| **MOSAIC STITCHER V3** | `000_Aerial_Mosaic_Stitcher_App_V3.html` | Zero-Mean Normalized Cross-Correlation (ZNCC) & L1 Pixel Difference Minimization |

---

### IV. SYSTEM PARAMETERS

| PARAMETER | SPECIFICATION |
| :---: | :---: |
| **EXECUTION ENGINE** | ECMAScript / HTML5 2D Canvas (`willReadFrequently: true`) |
| **MEMORY CEILING** | $16,777,216\text{ px}$ ($4096 \times 4096$) Hardware Allocation Guard |
| **NETWORK TELEMETRY** | Zero External Transmission / 100% Volatile Local Memory |
| **LICENSE** | MIT License — Copyright (c) 2026 Leon Christoffel Mynhardt Jordaan |

</div>
