# 🚀 Submission Guidelines

All submissions must be made through **GitHub Classroom** using a **COG-compliant Docker container**.

Your submission must:

- Accept an **ultrasound image** as input
- Return a **binary segmentation mask** as output (tumor vs. background)
- Follow the exact input/output format
- Be structured using COG with the required files listed below

---

## 📦 Required Files

Your repository should include:

- `cog.yaml`  
- `predict.py` (must contain the `Predictor` class with `setup()` and `predict()` methods)
- `model.py` (your model architecture)
- `best_unet_model.pth` (your trained model weights)
- Optionally, `Dockerfile` if advanced customization is needed

---

## ⚙️ Example `cog.yaml`

```yaml
build:
  python_version: "3.8"
  python_packages:
    - torch
    - torchvision
    - numpy
    - opencv-python
    - pillow

predict: "predict.py:Predictor"
