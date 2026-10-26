# Enterprise Ransomware Risk Assessment Tool

**Author:** Lestin D'souza\
**Project type:** Defensive cybersecurity risk assessment (educational
demonstration)

## Overview

This project is a small Python tool that scores and prioritizes
hypothetical enterprise ransomware risks. It multiplies a likelihood
rating by an impact rating, assigns a risk level, displays a prioritized
register, and exports the register to a CSV file.

## Scope and responsible use

This is a defensive awareness and planning tool. It does **not** create
or execute malware, encrypt files, scan networks, or test a real
organization. All risk entries are illustrative and contain no real
company information. The scores are examples, not measured probabilities
or a professional audit.

## Dataset

No external dataset is required. The notebook contains a small,
synthetic example risk register prepared solely for this project. It
covers employee endpoints, shared files, user accounts, backups,
applications, networks, incident response, third parties, sensitive
data, and staff awareness.

## Technologies

-   Python 3
-   Python standard library: `csv` and `pathlib`
-   Jupyter Notebook (`.ipynb`) format

## Risk scoring

-   Likelihood: 1 (rare) to 5 (almost certain)
-   Impact: 1 (minimal) to 5 (severe)
-   Score = likelihood × impact
-   1--4: Low; 5--9: Moderate; 10--16: High; 17--25: Critical

These thresholds are illustrative and should be tailored before
real-world use.

## Files

-   `Lestin_Dsouza_Enterprise_Ransomware_Assessment.ipynb` --- code,
    sample data, risk scoring, prioritization, and CSV export.
-   `requirements.txt` --- documents dependencies (none beyond Python's
    standard library).
-   `Lestin_Dsouza_ProjectReport.docx` --- project report.
-   `README.md` --- project overview and usage instructions.

## How to run

### Option A: Google Colab

1.  Open https://colab.research.google.com/
2.  Choose **File → Upload notebook** and upload the `.ipynb` file.
3.  Run each code cell from top to bottom.
4.  The notebook will create `ransomware_risk_register.csv` in the
    session's working directory. Download it from the Colab file panel
    if needed.

### Option B: Jupyter Notebook

1.  Install Python 3.10 or later.
2.  Install Jupyter Notebook if it is not already installed in your
    environment.
3.  Open the notebook in Jupyter.
4.  Run all cells from top to bottom.
5.  Find the exported `ransomware_risk_register.csv` in the working
    directory.

The notebook itself requires no third-party Python packages.
Jupyter/Colab is only the notebook environment.

## Key information

The tool helps demonstrate how a risk register can make risk discussions
more consistent and highlight where protective controls should be
reviewed first. It does not certify that a business is secure.

## References

-   NIST, *Cybersecurity Framework (CSF) 2.0*:
    https://www.nist.gov/cyberframework
-   CISA, *StopRansomware*: https://www.cisa.gov/stopransomware

## GitHub repository

Repository URL: **Add your public GitHub repository URL here after
creating the repository and uploading all deliverables.**
