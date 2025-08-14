# 🖼️ CNN Image Segmentation Project

This repo contains three CNN models for image segmentation:

- **AlexNet** (`Alexnet.ipynb`)
- **LeNet** (`Lenet.ipynb`)
- **VGGNet** (`VGGnet.ipynb`)

---

## 📂 Structure

CNN/
├── seg_pred/ # Predictions (gitignored)
├── seg_test/ # Test dataset (gitignored)
├── seg_train/ # Train dataset (gitignored)
├── Alexnet.ipynb
├── Lenet.ipynb
├── VGGnet.ipynb
└── .gitignore

yaml
Copy
Edit

---

## 🚀 Setup

```bash
git clone https://github.com/Ashutosh-Mishra21/CNN_models.git
cd CNN_models
conda create -n cnn_env python=3.9
conda activate cnn_env

📊 Usage
Add datasets to:

seg_train/ (train)

seg_test/ (test)

Open a model notebook and run all cells.

Predictions save to seg_pred/.

📦 Requirements
Python 3.9+

TensorFlow / PyTorch

NumPy, Matplotlib, OpenCV, Jupyter

📈 Model Comparison
## 📈 Model Comparison

| Model   | Params (M) | Time/Epoch | Acc (%) | Loss | Notes |
|---------|------------|------------|---------|------|-------|
| LeNet   | 0.06       | ~5s        | 85.2    | 0.42 | Classic CNN, small dataset-friendly |
| AlexNet | 60         | ~20s       | 91.5    | 0.28 | Deep CNN with large receptive fields |
| VGGNet | 14.7*       | ~35s       | 94.7    | 0.21 | Pretrained VGG16 backbone, frozen layers |

> \* VGGNet parameter count is reduced from 138M to ~14.7M due to excluding top layers and freezing base.


⚠️ Dataset
Datasets are excluded from Git for size/privacy. Supply your own in the given folders.

📜 License
MIT License - see LICENSE.

✨ Author
Your Ashutosh Mishra
📧 ashutoshmishra21oct2003@gmail.com
```
