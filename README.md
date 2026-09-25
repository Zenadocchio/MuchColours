# Real-World Acquisitions — Industrial IoT Segmentation (Muchcolours)

Supporting dataset for the paper *"Edge-Cloud Vision Foundation Models for Industrial IoT Segmentation: A Geometry-Aware and System-Level Study"* (M. Zenadocchio, C. Centofanti, C. Birra, G. De Vincentis, A. Rabuffo, V. Di Nino, L. Mostarda, A. Marotta), submitted to the *IEEE Internet of Things Journal*.

## Description

This repository contains a small set of real-world camera acquisitions, collected under the target industrial imaging conditions described in the paper (Sec. IV-A, "Dataset Construction and Industrial Image Generation"). They are used in the paper as a complementary, qualitative evaluation of the proposed segmentation framework, alongside the synthetic dataset that constitutes the paper's primary, statistically robust benchmark.

Each image shows multiple industrial objects placed on a printing bed and acquired under the target acquisition setup (uniform background, controlled illumination).

**No ground-truth instance masks are available for these acquisitions.** Accordingly, in the paper they are assessed qualitatively — through visual inspection of the predicted segmentation masks — rather than through the region-based and boundary-sensitive metrics (IoU, Dice, Boundary IoU) computed on the synthetic dataset.

## Contents

- `images/` — raw acquisitions (JPEG), numbered `001`–`007`.

## Usage

These images are provided as supporting reference material for the paper above. They are proprietary acquisitions made available by Muchcolours srl for this purpose; please contact the corresponding author before any reuse beyond reviewing or reproducing the results discussed in the paper.

## Citation

If you refer to this data, please cite the paper above (full citation to be updated upon publication).

## Contact

Matteo Zenadocchio — matteo.zenadocchio@graduate.univaq.it
Department of Information Engineering, Computer Science and Mathematics, University of L'Aquila, Italy.
