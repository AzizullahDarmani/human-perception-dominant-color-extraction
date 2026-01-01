# Dominant Color Extraction from Images  
A Comparative and Human-Perception–Driven Study

## Overview
This repository contains my final project for the course Artificial Intelligence: Fundamentals and Applications, focused on dominant color extraction from images.
The project focuses on a comparative study of clustering-based and feature-based methods and proposes a human-perception–driven approach to improve the alignment between extracted color palettes and human visual perception.

The work was conducted as part of a Computer Vision / Machine Learning course and follows an academic, research-oriented structure.

---

## Motivation
Dominant color extraction is widely used in applications such as image retrieval, design, and visual summarization.  
Many existing methods rely on pixel-level clustering in RGB space, which often fails to reflect how humans perceive color.

This project aims to:
- Compare classical and perception-aware color extraction methods
- Analyze their strengths and limitations
- Propose an approach that better matches human visual perception

---

## Methods Compared
The following methods were implemented and evaluated:

- **RGB K-means clustering**
- **CIELAB-based K-means clustering**
- **Feature-based dominant color extraction** (based on existing academic literature)
- **Proposed human-perception–driven approach**, integrating:
  - Perceptual color space (CIELAB)
  - Saliency and region-level analysis
  - Reduced sensitivity to background noise

---

## Evaluation
The methods were evaluated using both qualitative and quantitative criteria:

- Visual comparison of extracted color palettes
- Perceptual color distance (ΔE) in CIELAB space
- Analysis of failure cases and limitations

---

## Key Findings
- CIELAB-based clustering produces more perceptually meaningful color palettes than RGB clustering
- Pixel-level clustering alone is sensitive to noise and background regions
- Incorporating perceptual color space and region-level information improves alignment with human perception

---

## Academic Integrity
This project is an original academic work.  
All referenced methods and prior research are properly cited in the project report.  
The comparative analysis, evaluation, and proposed approach were independently implemented and analyzed.

---

## Notes
- The project report is included as a PDF in this repository
- Code and experiments are provided for academic and learning purposes


