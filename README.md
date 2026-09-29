# dvc-demo1

A small demo of data version control (DVC).

## Contents

- `.dvc/`, `.dvcignore`: DVC setup
- `data/raw.dvc`: the raw dataset tracked by DVC instead of git
- `src/data_ingestion.py`: reads the loan approval dataset with Pandas

The dataset path in `data_ingestion.py` is a local Windows path (`D:\loan_approval_dataset.csv`); change it to where your copy is.
