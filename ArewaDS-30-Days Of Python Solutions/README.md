# ArewaDS Python Programming Fellowship Exercises

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg)](https://jupyter.org/)
[![Fellowship](https://img.shields.io/badge/Arewa%20Data%20Science-Fellowship-green.svg)](https://github.com/arewadataScience/30-Days-of-Python)

This repository contains my solutions to the **30 Days of Python** challenge from the **Arewa Data Science (ArewaDS) Python Programming Fellowship**.

The challenge topics were covered in the fellowship's weekly classes, so the exercises are organised into **six weekly folders (Week 1 to Week 6)**, each grouping the topics taught that week. Every exercise is written as a Jupyter Notebook (`.ipynb`) and can be run top to bottom.

## About the Author

| | |
|---|---|
| **Name** | Umar Muhammad Suleman |
| **Age** | 26 |
| **Programme** | Arewa Data Science Fellowship, Python Programming |

## Repository Structure

```
.
├── README.md
├── Week_1/
│   └── variables.ipynb
├── Week_2/
│   ├── list.ipynb
│   ├── set.ipynb
│   └── tuple.ipynb
├── Week_3/
│   ├── conditionals.ipynb
│   └── dictionaries.ipynb
├── Week_4/
│   ├── functions.ipynb
│   └── loop.ipynb
├── Week_5/
│   └── classes.ipynb
├── Week_6/
│   └── date_file_handling.ipynb
└── data/
    ├── countries_data.json
    ├── donald_speech.txt
    ├── melina_trump_speech.txt
    ├── michelle_obama_speech.txt
    └── obama_speech.txt
```

## Weekly Breakdown

| Week | Topics Covered | Notebook(s) |
|:---:|---|---|
| **1** | Variables, built-in functions, operators and strings | `variables.ipynb` |
| **2** | Lists, tuples and sets | `list.ipynb`, `tuple.ipynb`, `set.ipynb` |
| **3** | Conditionals and dictionaries | `conditionals.ipynb`, `dictionaries.ipynb` |
| **4** | Loops, functions and list comprehensions | `loop.ipynb`, `functions.ipynb` |
| **5** | Classes and objects | `classes.ipynb` |
| **6** | File handling, regular expressions and date/time | `date_file_handling.ipynb` |

## Datasets

The `data/` folder holds the files used by the exercises:

- `countries_data.json`: country data used in the loops and file-handling exercises (languages, populations).
- `donald_speech.txt`, `melina_trump_speech.txt`, `michelle_obama_speech.txt`, `obama_speech.txt`: speech texts used for line, word and text-analysis exercises.

## How to Run

1. Clone or download this repository.
2. Install Jupyter and the libraries used:
   ```bash
   pip install notebook pandas scikit-learn
   ```
3. Start Jupyter from the repository root and open any notebook:
   ```bash
   jupyter notebook
   ```

Notebooks in the weekly folders read datasets with relative paths such as `../data/countries_data.json`, so keep the folder layout unchanged.

## Notes

- Exercises are grouped by the week in which the topics were taught, not one folder per day.
- Some Week 6 exercises use files that are not included in this repository (for example `email_exchange_big.txt`, a stop-words file and `hacker_news.csv`); add them to `data/` to rerun those cells.
- `obama_speech.txt` and `Week_2/list.ipynb` are currently empty.

## Acknowledgements

Thanks to the **Arewa Data Science** team and instructors for the fellowship and the 30 Days of Python curriculum.
