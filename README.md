# 📌 ImageStitchingCPP-BoschProject

This repository presents a C++-based image stitching application built using OpenCV. The project was developed as part of the **Bosch Autovision Challenge**, showcasing a robust approach to stitching multiple images into a panorama using ORB features and homography-based alignment.

---

## 🧠 Project Overview

This application:
- Accepts multiple input images via CLI
- Detects keypoints and computes descriptors using ORB
- Matches features and performs homography estimation
- Stitches the images together into a panoramic output
- Includes static-linked executables and pre-generated results for demo purposes

> 📄 Complete documentation, including setup and technical notes, can be found in `BoschAutovisionX_1Neuron.docx`.

---

## 🗂️ Repository Structure

```plaintext
Project3/
├── Project3/              # Source files (CAF.cpp, FileName.cpp)
├── x64/
│   └── Release/
│       ├── DesiredOutput/  # Sample stitched results
│       └── Project3.exe    # CLI executable
├── StaticLinkedExecutable/ # Statically linked version (no dependencies)
└── BoschAutovisionX_1Neuron.docx  # Detailed report and setup guide

