# Solar and Stellar Flare Dataset and Models

This repository provides data and pre-trained models related to solar and stellar flare research. We release two zip archives for users to download and explore:

---

## 📁 Available Downloads

👉 **[Releases Page with Download Links](https://github.com/astor-sy/my-model-share/releases)**

### 1. `solar.zip`

This package includes data and models related to solar flares:

- `dataset/`
  - Contains training (`train`) and testing (`test`) datasets
- `catalog.csv`
  - Catalog of solar flares, including labels, start time, peak time, end time, and the GOES satellite number used for each event
- `model/`
  - Pre-trained solar flare classification model
- `train_results/`
  - Training results and evaluation metrics for the solar flare model

### 2. `stella.zip`

This package contains data and models for stellar flares (main-sequence stars only):

- `catalog.csv`
  - Catalog of stellar flare events
- `flare_energy.csv`
  - Energy estimates for each stellar flare
- `stella_params_with_type.csv`
  - Stellar parameters with classification
- `features.csv`
  - Extracted features for each stellar flare event
- `flare_split/`
  - Subsamples of stellar flares grouped by F, G, K, and M-type main-sequence stars

---

## 🚀 Usage

1. Go to the [Releases page](https://github.com/astor-sy/my-model-share/releases) to download `solar.zip` and `stella.zip`.
2. Unzip the files locally.
3. Follow the directory structure described above to access the datasets, models, and documentation.

---

## 📌 Notes

- All stellar flare samples in this dataset are **main-sequence stars**.
- The solar data is based on GOES satellite observations, fully documented in the included `catalog.csv`.

If you use these datasets or models in your research, please consider citing this repository.

---

## 📫 Contact

If you have any questions, please open an issue or contact us at:
- GitHub: [astor-sy](https://github.com/astor-sy)

Enjoy exploring solar and stellar flares!


