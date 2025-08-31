# How To install Miniconda On Mac

Miniconda is a lightweight distribution of Anaconda that includes only `conda`, Python, and a few essential packages.  
It is ideal for setting up Python environments in a flexible and minimal way.

---

## 📥 1. Download Installer
select version 

- **Intel (x86_64) - before apple use silicon processor  
  [Miniconda3-latest-MacOSX-x86_64.sh](https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh)  
- **Apple Silicon (M1/M2, arm64)
  [Miniconda3-latest-MacOSX-arm64.sh](https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh)

📖 Reference: [Miniconda Official Docs](https://docs.conda.io/en/latest/miniconda.html)

---

## 🖥️ 2. Installation Step by Step

### Navigate to the download folder
example location: cd ~/Downloads

### Run the installer
bash Miniconda3-latest-MacOSX-x86_64.sh

Follow the prompts:
- Press Enter to read the license.
- Type yes to accept the license.
- Press Enter to use the default installation location.
- Type yes when asked to run conda init.

### Integrate with your shell (example for zsh):
source ~/miniconda3/bin/activate
conda init zsh

### Verify Installation
Run:
conda list

# 3. Basic Conda Commands
### Activate the base environment
conda activate

### Create a new environment with Python 3.9
conda create -n myenv python=3.9

### Activate the new environment
conda activate myenv

# List available environments
conda env list
