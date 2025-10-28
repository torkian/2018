# MNIST Logistic Regression (PyTorch → ONNX)

This project shows how to:
- Load and preprocess MNIST
- Train a simple **multiclass logistic regression classifier**
- Save sample inputs/outputs/weights
- Export the trained model to **ONNX**
- Run inference using **ONNX Runtime**

---

## 1) Install Requirements

```bash
pip install torch torchvision numpy onnx onnxruntime
