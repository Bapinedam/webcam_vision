# webcam_vision 

By: Brayam Pineda.

Version: 0.1.0

It's the typical project that you post in linkedin where the camera identify your face

## Create environment

```bash
conda env create -f environment.yml
activate webcam_vision
```

or 

```bash
mamba env create -f environment.yml
activate webcam_vision
```

## Project organization

    webcam_vision
        ├── data
        │   ├── processed      <- The final, canonical data sets for modeling.
        │   └── raw            <- The original, immutable data dump.
        │
        ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
        │                         the creator's initials, and a short `-` delimited description, e.g.
        │                         `1.0-initial-data-exploration`.
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    <- The requirements file for reproducing the analysis environment.
        │
        └── README.md          <- The top-level README for developers using this project.

---
