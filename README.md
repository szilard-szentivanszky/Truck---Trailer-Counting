# Truck-Trailer-Counting

## Project Description
The goal of the Truck Counter Project is to create an efficient and accurate system capable of detecting and counting trucks in video footage. This can be useful for traffic analysis, logistical planning, and traffic safety applications..

---

## Features and Functionalities
- **Data Preparation**: Splitting data into training, validation, and test sets.
- **Model Training**: Fine-tuning deep learning models.
- **Validation and Testing**: Evaluating model performance on unseen data.

---

## Hardware Environment
- **CPU**: Intel(R) Core(TM) i7-8700 @ 3.20GHz
  - Processor Clock Speed: 3700 MHz
  - Cores: 6
  - Threads: 12
- **RAM**: DDR4, 48 GB, 2666 MHz
- **GPU**: GeForce® RTX 2070 SUPER™
  - CUDA® Cores: 2560
  - Memory Clock: 14000 MHz
  - Core Clock: 1815 MHz
  - Memory Size: 8 GB
  - Memory Type: GDDR6
  - Memory Bus: 256-bit
  - Memory Bandwidth: 448 GB/s

---

## Software Environment
- **Operating System**: Windows 11 Pro (x64-based)
- **Development Tools**: Jupyter Notebook 7.x
- **Deep Learning Framework**: PyTorch 2.x

---

## Data Format and Structure
The dataset comprises video footage of trucks and trailers. Data preparation scripts include tools for splitting the dataset into training, validation, and testing subsets.

---

## Installation

Before running the project, install the required packages:

```bash
pip install pandas numpy torch torchvision yolo opencv-python ultralytics PIL glob2
---
## Package Versions

The following package versions were used in this project:

| Package               | Version      |
|-----------------------|--------------|
| `torch`              | 2.0.1+cu117  |
| `torch_snippets`     | 0.544        |
| `torch-summary`      | 1.4.5        |
| `torchaudio`         | 2.0.2+cu117  |
| `torchmetrics`       | 1.2.0        |
| `torchsummary`       | 1.5.1        |
| `torchvision`        | 0.15.2+cu117 |
| `tornado`            | 6.3.2        |
| `numpy`              | 1.26.4       |

## Data Format and Structure
The dataset comprises video footage of trucks and trailers. Data preparation scripts include tools for splitting the dataset into training, validation, and testing subsets.

### Dataset Directory Structure

dataset(images+lables)/
├── images+lables/
  ├── train/     # Training images+labels
  ├── val/       # Validation images+labels
  └── test/      # Test images+labels


