# Columbia University — Computer Vision Portfolio

> **Projects:** GANs • Edge Detection • View Synthesis  
> **Stack:** Python · NumPy · OpenCV · PyTorch · Jupyter

This portfolio showcases compact, end‑to‑end projects completed as part of the **First Principles of Computer Vision (Columbia University)** path. Each project emphasizes first‑principles reasoning, clarity, and reproducibility.

---

## 🔎 At a Glance
- **Edge Detection (from scratch):** manual convolution → Sobel gradients → NMS → hysteresis.  
- **GANs (DCGAN, PyTorch):** generator/discriminator, stability tricks, sample grids over epochs.  
- **Two‑View Geometry + View Synthesis:** features + matching, essential matrix, pose recovery, naive novel‑view synthesis.
- **Jupyter‑first workflow:** every project is runnable with one environment (`requirements.txt`).

---

## 📂 Repo Structure

```
columbia-computer-vision/
├─ columbia_cv_portfolio_FULL_FINAL/     # cleaned notebooks, models, visuals
├─ notebooks/                            # (optional) individual project notebooks
├─ src/                                  # reusable modules
├─ results/                              # figures & example outputs
├─ requirements.txt
└─ README.md
```

> Note: exact paths may differ; this README focuses on outcomes and how to run.

---

## 📁 Project Folder Included
- **`columbia_cv_portfolio_FULL_FINAL/`**  
  Contains cleaned‑up notebooks, models, and visuals (final versions used for review).

---

## 📘 Course Info
**Institution:** Columbia University  
**Specialization:** First Principles of Computer Vision  
**Tools Used:** Python, OpenCV, PyTorch/TensorFlow (as applicable), NumPy, Matplotlib, Jupyter Lab

---

## 🚀 Quickstart

```bash
# 1) (Recommended) create a virtual env
python -m venv .venv
# macOS/Linux:
source .venv/bin/activate
# Windows:
# .venv\Scripts\activate

# 2) Install dependencies
pip install --upgrade pip
pip install -r requirements.txt

# 3) Launch notebooks
jupyter notebook    # or: jupyter lab
```

---

## 📊 Results (snapshots to add)
When running locally, artifacts are saved under `/results`.  
Please add 2–3 best images here after your next run (drag‑drop into this README):

- **Edges:** before/after comparison (`results/edges/*.png`)  
- **GANs:** sample grids across epochs (`results/gan/grid_epoch_*.png`)  
- **View Synthesis:** matches + synthesized view (`results/view/*.png`)

---

## 🧪 Repro Tips
- Seed NumPy/Torch and (optionally) set `torch.backends.cudnn.deterministic = True`.  
- Keep datasets outside Git; point notebooks to your local `data/` directory.  
- Save intermediate visual checks into `/results` to make review fast.

---

## 🔖 License
MIT (optional). If you want others to reuse code, add a `LICENSE` file with MIT text.

---

## 📬 Contact
Feel free to connect or collaborate:

- **Email:** pshivaanichauhan@gmail.com  
- **LinkedIn:** https://www.linkedin.com/in/priya-shivaani-chauhan  
- **Portfolio (GitHub):** https://github.com/pshivaanichauhan

---

### Recruiter Note
These projects were selected to demonstrate both **first‑principles understanding** and **practical engineering**. Notebooks run end‑to‑end with comments on design choices, trade‑offs, and next steps.
