# Psychometric evaluation of the 5-item Medication Adherence Report Scale questionnaire in persons with multiple sclerosis

[![CC BY 4.0][cc-by-shield]][cc-by]

---
[About](#about) | [Code](#code) | [Data organization](#data-organization) | [Citation info](#citation-info) | [License](#license)

--- 
## About

The 5-item Medication Adherence Report Scale (MARS-5) is a reliable and valid questionnaire to evaluate adherence in patients with asthma, hypertension and diabetes. So far, validity has not been determined for persons with multiple sclerosis (MS). The aim of this study was to establish criterion validity of the MARS-5 in persons with MS.

The manuscript resulting from this study is currently under review.

This repository provides the code used to obtain study results. However, due to sensitive patient information **the data used in this study cannot be made publicly available**.

---
## Code

The code was developed in programming language R (version `3.3.0`) and executed in [R Studio](https://posit.co/download/rstudio-desktop/) (version `2023.06.2+561`).

The file `MARS_MS.R` contains all the codes necessary to reproduce results in the present study. The libraries required to run the code are listed in the preamble of the R script. 


Please modify the code by including your data in the following two lines: 
```R
dfPts_mars <- xl.read.file( , password =)
dfRx_mars <- xl.read.file(, password =)
```

Please refer to the [Data organization](#data-organization) section in order to see how to prepare the data files.

**ADD FURTHER NOTES ABOUT THE CODE IF NECESSARY**

---
## Data organization

The data should be organized into two Excel files, e.g.:

- *pts.xlsx*: NEED TO ADD GENERAL DESCRIPTION
- *rx.xlsx*: NEED TO ADD GENERAL DESCRIPTIONS

The file *pts.xlsx* should contain the following column names:

- *col1*: ADD DESCRIPTION AND FORMAT
- *col2*: ADD DESCRIPTION AND FORMAT
- *col3*: ADD DESCRIPTION AND FORMAT
- *col4*: ADD DESCRIPTION AND FORMAT


The file *rx.xlsx* should contain the following column names:

- *col1*: ADD DESCRIPTION AND FORMAT
- *col2*: ADD DESCRIPTION AND FORMAT
- *col3*: ADD DESCRIPTION AND FORMAT
- *col4*: ADD DESCRIPTION AND FORMAT


---
## Citation

If you find this work interesting or re-use our code for your purposes we kindly ask you to cite the following paper in your publications:

```plaintext
Jožef, Maj, Locatelli, Igor, Brecl Jakob, Grega, Savšek, Lina, Šurlan Popović, Katarina, Špiclin, Žiga, Rot, Uroš, Kos, Mitja. (2022). Psychometric evaluation of the 5-item Medication Adherence Report Scale questionnaire in persons with multiple sclerosis. In review. 2023
```

If using BibTex please cite this paper as:
```bibtex
@article{mjozef2023mars5,
    title={Psychometric evaluation of the 5-item Medication Adherence Report Scale questionnaire in persons with multiple sclerosis},
    author={Jo\v{z}ef, Maj, Locatelli, Igor, Brecl Jakob, Grega, Sav\v{s}ek, Lina, \v{S}urlan Popovi\'{c}, Katarina, \v{S}piclin, \v{Z}iga, Rot, Uro\v{s}, Kos, Mitja},
    journal={In review},
    volume={n/a},
    number={n/a},
    pages={n/a},
    year={2023},
    publisher={n/a}
}
```


---

## License

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg