# Automated Job Listing Collection — Demo Website

## Overview
Python requests and BeautifulSoup parse job cards from the public, deliberately fictional Real Python fake jobs sample and export a jobs.csv file.

## Tools
requests, beautifulsoup4.

## Data source / permissions
Source: https://realpython.github.io/fake-jobs/ . These 100 listings are fictional examples, not live recruitment vacancies.

## Analysis and results
The notebook output reports HTTP 200 and 100 extracted sample job listings. The Colab download cell requires Google Colab.

## How to run
1. Create a Python environment and install packages from `requirements.txt`.
2. Open `notebooks/analysis.ipynb` in Google Colab or Jupyter.
3. Run cells sequentially; external datasets/downloads may be required.
4. For the process-mining notebook, obtain the authorized input event log and update the hard-coded filepath before running.

## Notes
- The analysis notebook preserves the submitted student's original code cells; saved outputs have been removed to avoid leaking data and to reduce repository size.
- This packaging step **did not re-execute or independently validate** the notebooks.
- Educational/demonstration project, not a deployed production system.
