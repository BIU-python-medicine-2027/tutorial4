# Tutorial 4 — DNA ORFs

Practice for lecture 4. Work through the ORF notebook and the helper module.

<a href="https://colab.research.google.com/github/BIU-python-medicine-2027/tutorial4/blob/main/orf.ipynb" target="_blank" rel="noopener noreferrer"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## Files

| File | Role |
| --- | --- |
| `orf.ipynb` | Step-by-step practice |
| `orf.py` | Functions to implement / try |
| `orf_solution.py` | Reference solution (peek only after trying) |

Suggested functions: `find_all_starts`, `find_first_in_register_stop`, `all_orfs_range`, `longest_orf`.

## How to work

1. Open the notebook in Colab (button above) or locally.
2. After each function, run the **self-check** cell below it (same cases as the autograder, with expected / got / hint).
3. Copy your finished functions into `orf.py` and **Commit changes** to see the autograding score (10 points, practice only).

## Grading — 10 points

| Check | Points |
| --- | ---: |
| `find_all_starts` — no ATG | 1 |
| `find_all_starts` — several ATG | 1 |
| `find_all_starts` — mixed frames / upper-case | 1 |
| `find_first_in_register_stop` — no in-frame stop | 1 |
| `find_first_in_register_stop` — in-frame stop | 1 |
| `all_orfs_range` — no ORFs | 1 |
| `all_orfs_range` — simple ORFs | 1 |
| `all_orfs_range` — several frames | 1 |
| `longest_orf` — no ORF | 1 |
| `longest_orf` — longest of several (case-insensitive input) | 1 |

## Optional: keep your changes in Google Drive

In Colab: **File → Save a copy in Drive**.
