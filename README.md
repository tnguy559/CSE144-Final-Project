# CSE144-Final-Project

How to Train
This project runs on Kaggle Notebooks with a free GPU. Open cse144-final-project.ipynb, attach the competition dataset as input, enable GPU and Internet in Session Options, then run all cells from Step 1 through Step 7 sequentially. Training runs for 30 epochs and automatically saves the best checkpoint based on validation accuracy.

Reproducibility
Random seed 42 is fixed globally at the start of the notebook. The train/val split uses torch.Generator().manual_seed(42) and deterministic algorithms are enabled. Environment: Python 3.12.12, PyTorch 2.x, TorchVision, Kaggle GPU (CUDA). All dependencies are pre-installed in Kaggle Notebooks with no additional installation required.

<img width="935" height="765" alt="image" src="https://github.com/user-attachments/assets/e9669deb-f2c0-4686-931d-598718eeb78d" />
