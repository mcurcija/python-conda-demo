# Python Conda Demo

A simple Python project demonstrating how to manage environments using Conda. This project includes a script `pi.py` that utilizes `numpy` to display the value of PI.

## Prerequisites

To run this project, you need to have **Conda** installed on your system. We recommend using **Miniconda** (a lightweight version) or **Anaconda**.

### Installing Conda (Linux)

1.  **Download the Miniconda installer:**
    ```bash
    curl -O https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
    ```
2.  **Run the installer:**
    ```bash
    bash Miniconda3-latest-Linux-x86_64.sh
    ```
3.  **Follow the prompts** on the screen. It is recommended to allow the installer to initialize Miniconda by running `conda init`.
4.  **Restart your terminal** or run `source ~/.bashrc` to apply the changes.

For other operating systems, please refer to the [official Miniconda installation guide](https://docs.conda.io/en/latest/miniconda.html).

## Setup Instructions

Once Conda is installed, follow these steps to set up the project environment:

### 1. Create the Environment

Create the project environment from the provided `environment.yml` file:

```bash
conda env create -f environment.yml
```

### 2. Activate the Environment

Activate the newly created environment:

```bash
conda activate python-conda-demo
```

## Usage

After activating the environment, you can run the demonstration script:

```bash
python pi.py
```

This should output:
`The value of PI from numpy is: 3.141592653589793`
