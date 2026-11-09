# mango-leaf-xds

# Explainable Mango Leaf Disease Classification

A Grad-CAM-based decision-support tool for agricultural field officers triaging farmer-submitted leaf photos.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SwelSwel/mango-leaf-xds/blob/main/Mango_Leaf_XDS.ipynb)

## How to run

1. Click the "Open in Colab" badge above
2. In the config cell, set `MANGO_QUICK = "0"` for the full run
3. **Runtime → Run all**
4. First run takes ~30–40 minutes on a T4 GPU. Checkpoints save to Google Drive, so reruns take ~10–15 minutes.

**Dataset:** MangoLeafBD downloads automatically via `kagglehub` on first run. If you already have it, place the zip at `MyDrive/XDS/MangoLeafBD Dataset.zip` to skip the download.

## Repository contents

```
mango-leaf-xds/
├── README.md
├── requirements.txt
└── Mango_Leaf_XDS.ipynb    ← everything runs from this notebook
```
