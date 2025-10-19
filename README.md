# mlprojects

<!-- Header image -->
<p align="center">
  <img src="./assets/ml.svg" alt="mlprojects" width="600" />
</p>

This is my elegant collection of Machine Learning and Deep Learning Jupyter notebooks.

---

## Table of contents

- Notebooks
- Requirements
- How to run

## Notebooks

Files included (each is a Jupyter notebook `.ipynb`):

- `Aspect-Based Sentiment Analysis.ipynb` — Aspect-based sentiment analysis.
- `Breast Cancer Detection.ipynb` — Breast cancer detection (image/deep learning).
- `DeepFake Detection.ipynb` — DeepFake detection.
- `Hand Skin Detection.ipynb` — Hand skin region detection.
- `Image Inpainting.ipynb` — Image inpainting with deep models.
- `Image Retrieval.ipynb` — Image retrieval techniques.
- `Machine Translation.ipynb` — Machine translation (seq2seq / Transformer).
- `Medical NER.ipynb` — Medical named entity recognition.
- `Poem Generation.ipynb` — Poem generation with language models.
- `Point Cloud Classification.ipynb` — 3D point cloud classification.
- `Scene Text Recognition.ipynb` — Scene text recognition (OCR in images).
- `Style Transfer.ipynb` — Neural style transfer for images.
- `Text Classification.ipynb` — Text classification examples.
- `Traffic Sign Detection.ipynb` — Traffic sign detection.
- `Visual Question Answering.ipynb` — Visual Question Answering (VQA).

## Requirements

- Python 3.8+ and Jupyter Notebook / JupyterLab.
- Install common libraries per-notebook as needed, for example:

```
numpy pandas matplotlib scikit-learn torch torchvision tensorflow transformers opencv-python
```

Use a virtual environment (venv or conda) to keep dependencies isolated.

## How to run

1. Open a terminal and change directory to the repository root.
2. Create and activate a virtual environment.

   Windows (PowerShell):

   ```powershell
   python -m venv .venv; .\.venv\Scripts\Activate.ps1
   ```

   Conda:

   ```powershell
   conda create -n mlprojects python=3.9 -y; conda activate mlprojects
   ```

3. Install JupyterLab if needed: `pip install jupyterlab`.
4. Start JupyterLab: `jupyter lab` and open the notebooks.