# Anime Dataset Feature Extraction & Analysis using Python

A Data Analysis and Feature Engineering project using **Python** and **Pandas** to extract, transform, and analyze key information from an uncleaned anime dataset.

---

## Project Overview

Raw datasets often contain unstructured text columns that combine multiple pieces of information. In this project, an uncleaned dataset containing anime rankings (`anime.csv`) was processed to extract numerical and temporal features from complex text strings.

### Key Objectives:
- Extract episode counts from unstructured text fields using custom parsing functions.
- Extract broadcast date ranges (start and end months/years).
- Compute total duration (in months) using standard library datetime utilities.
- Perform exploratory data analysis (EDA) to find top-rated, longest-running, and high-episode count anime.

---

## Tech Stack & Dependencies

- **Language:** Python 3.x
- **Data Manipulation:** `pandas`, `numpy`
- **Date & Time Operations:** `datetime`, `python-dateutil` (`relativedelta`)

