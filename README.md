# Machine Learning Homework

This repository contains my machine learning homework assignments: code, notebooks, and write-ups.

## Repository Structure

```
.
├── hw1/
│   ├── hw1.ipynb
│   └── ...
├── hw2/
│   └── ...
├── data/               # not tracked (see "Data" below)
│   └── README.md
├── requirements.txt
├── .gitignore
└── README.md
```

> Update this tree to match the actual folders and files in the repo.

## Setup

```bash
git clone https://github.com/<username>/<repo>.git
cd <repo>

python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

pip install -r requirements.txt
```

## Data

**Datasets are not included in this repository.**

This is intentional, for three reasons:

- **Size.** Datasets and model checkpoints are often large. GitHub rejects files over 100 MB, and even smaller files permanently bloat the repo history.
- **Licensing and course policy.** Some datasets can't be redistributed, and course-provided data shouldn't be published publicly.
- **Reproducibility.** Processed data, model outputs, and checkpoints can be regenerated from the code, so only the code is tracked.

Data files (`data/`, `*.csv`, `*.pt`, `*.pth`, `*.h5`, `*.ckpt`, etc.) are listed in `.gitignore`.

### Getting the data

Download each dataset from its source and place it in the `data/` folder (or the path the assignment's code expects):

| Assignment | Dataset | Source | Expected path |
|------------|---------|--------|---------------|
| HW1 | `<dataset name>` | `<link>` | `data/<file>` |
| HW2 | `<dataset name>` | `<link>` | `data/<file>` |

> Fill in the table for each assignment. If a dataset was provided by the course, note that it is available through the course site.

Small sample files, if any, are committed so the code can run without the full dataset.

## Running the Code

Each assignment folder is self-contained. Open the notebook or run the script from inside that folder:

```bash
cd hw1
jupyter notebook hw1.ipynb
```

## Author

Gauransh