# Gradient-Ascent-Feature-Visualization
Investigating and cross-analyzing class-specific feature visualizations across pretrained Convolutional Neural Networks (**VGG-16**, **VGG-19**, and **ResNet-152**) using gradient ascent. This project explores how optimization techniques, specifically $L_2$ regularization and Gaussian blur smoothing impact visual interpretability and cross-model transferability.

For the complete problem definition, methodology, and implementation details, refer to the [Jupyter Notebook](./src/main.ipynb).

## Environment Setup

This project provides Conda environment configurations for CPU and GPU setups across Windows and Unix-based systems.
The following assumes Conda is installed on your system.

### 1. Clone the Repository

    git clone https://github.com/O-Brob/Gradient-Ascent-Feature-Visualization.git
    cd Gradient-Ascent-Feature-Visualization

### 2. Create the Conda Environment
Select the configuration file from the conda-environment-files/ directory that matches your operating system and hardware setup.
e.g. if using Linux with a GPU: `conda env create -f conda-environment-files/conda-environment-gpu-unix.yml`
where `gpu` is interchangeable with `cpu` and `unix` with `win`.

### 3. Activate the Environment
    conda activate dml

### 4. Launch Jupyter Notebook
    jupyter notebook
