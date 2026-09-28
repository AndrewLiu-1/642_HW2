# MSML642 Homework 2 materials

This package accompanies the existing HW2 assignment PDF. The **student notebook** is the only notebook to share with students. The executed answer notebook belongs in a staff-only location; do not put it in the student Drive folder.

## Run

Use Python 3.12.11. From this directory, create an environment and install the tested versions:

```bash
python3.12 -m venv .venv
.venv/bin/python -m pip install -r requirements.txt
```

Open `MSML642_HW2_Starter.ipynb` with the same environment's Python kernel. The notebook loads `datasets/airline_passengers.csv` if present and otherwise uses its public URL. The reference answer was run on CPU; exact model metrics can vary by platform despite the fixed seed.

## Data

The `datasets/` directory contains the main airline-passenger CSV and a **representative subset** of each of the five optional bonus datasets. The bonus files are not needed for the required RNN/LSTM assignment. Source links, citations, and file hashes are in `datasets/SOURCES.md`.

The NASA archive contains a nested ZIP. The Robot Execution Failures archive contains an old executable (`a.out`); do not run it. Read only the data files. The MR.CLAM copy contains only Robot 1 ground truth and odometry from Dataset 3, not the complete nine-dataset collection.
