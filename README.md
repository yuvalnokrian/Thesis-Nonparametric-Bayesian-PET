# Nonparametric Bayesian Regularization in PET Image Reconstruction via Oracle Shrinkage

This repository contains the core implementation of the research work for an M.Sc. thesis at the School of Mathematical Sciences, Tel Aviv University. The project explores advanced statistical regularization methods for Positron Emission Tomography (PET) using the **Oracle Gibbs** algorithm.

## 🚀 Overview
Traditional PET reconstruction methods like OSEM often suffer from high noise levels, while regularized methods like BSREM require careful tuning of the $\beta$ parameter. This project implements a Nonparametric Bayesian approach that performs adaptive shrinkage to provide superior image quality and diagnostic contrast.

## 🛠 Main Features
- **PET Simulation Engine:** Full physics simulation including Poisson noise, randoms, and attenuation.
- **Algorithm Implementations:**
  - Standard OSEM (Ordered Subsets Expectation Maximization).
  - Optimized BSREM (Block Sequential Regularized Expectation Maximization) with automated Grid Search.
  - **Oracle Gibbs:** The proposed Bayesian shrinkage framework.
- **Evaluation Suite:** Comprehensive metrics calculation (RMSE, SNR) and localized ROI analysis for clinical lesions.
- **Visualization:** Automated plotting of U-curves, profile comparisons, and reconstructed images.

## 📁 Repository Structure
- `pet_oracle_reconstruction.py`: The primary execution engine for simulations and reconstructions.
- `final_thesis_production/`: Output directory containing generated plots and results (CSV).
- `requirements.txt`: List of necessary Python libraries.

## 💻 Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/YourUsername/PET-Oracle-Reconstruction.git](https://github.com/YourUsername/PET-Oracle-Reconstruction.git)
