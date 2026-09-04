# Data

This directory contains the two datasets used in the paper **Intrinsic Particle Optimization for Hex-Dominant Meshing**: **HDIM** and **MAMBO-Basic**.

## File Description

| File                  | Type   | Description                             |
| --------------------- | ------ | --------------------------------------- |
| `input.vtk`           | input  | Input mesh with density field           |
| `fl.fl`               | input  | Feature lines                           |
| `conforming.vtk`      | output | Hexahedral mesh (conforming)            |
| `non-conforming.vtk`  | output | Hexahedral mesh (non-conforming)        |

## Note

Some models only have input files and no `conforming.vtk` / `non-conforming.vtk`,
meaning that hexahedral meshing failed for those models and no result was produced.
