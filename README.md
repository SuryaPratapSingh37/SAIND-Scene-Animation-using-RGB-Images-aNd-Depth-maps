# SAIND-Scene-Animation-using-RGB-Images-aNd-Depth-maps

## :wrench: Installation
1. Clone this repo:
    ```bash
    git clone https://github.com/SuryaPratapSingh37/SAIND-Scene-Animation-using-RGB-Images-aNd-Depth-maps.git
    ```
2. Install dependent packages:
  After installing [Anaconda](https://www.anaconda.com/), create a new Conda environment using `conda create --name saind_env --file requirements.txt`.

## Project Architecture

```
├── LDC
    ├── checkpoints
        ├──MDBD/5/5_model.pth
    ├── data                        # Paste your Images here for running edge detection
    |   ├── (Some images)           # Images to test LDC
    ├── result/MDBD2CLASSIC         # Edge maps will be generated here
    ├── utils                       # A series of tools used in this repo
    |   └── img_processing.py       # Miscellaneous tool functions
    ├── datasets.py                 # Tools for dataset managing 
    ├── losses2.py                  # Loss function used to train DexiNed (BDCNloss2)
    ├── main.py                     # The main python file with main functions and parameter settings
                                    # here you can test and train
    ├── modelB4.py                  # LDC (4 blocks) class in pytorch
    └── modelB5.py                  # LDC (5 blocks) class in pytorch
```
