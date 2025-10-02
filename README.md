![](acadmathsci-logo.png)
# mathsci-econ-contrib2.0
New best estimates for the UK's mathematical science (MS) workforce and its associated economic contributions in 2024 and beyond.

## Background

In a [2025 report](https://zenodo.org/records/17117973), the Academy for the Mathematical Sciences derived new best estimates for the UK's mathematical science (MS) workforce and its associated economic contributions in 2024. These new estimates benefit from several methodological refinements to previous work, as well as the availability of newer, more comprehensive data sets. 

We calculated that 5.11 million people were working in mathematical science occupations in 2024, representing 15% of all UK employment, and that those workers directly contributed £489 billion to the UK economy in 2024, representing 19% of total UK gross value added (GVA). Our new analysis also identified the occupations and industries where the mathematical sciences play particularly significant roles in the UK.

This repository contains a Jupyter notebook with the code used to perform the analysis leading to those estimates.

## How to use
The code has been tested with Python > 3.10.16 (though is likely to work with earlier versions of Python 3.x).

### Dependencies
| Library | Required? | Relevance |
| :-- | :-- | :-- |
numpy | ✅ | Linear algebra and array operations |
scipy | ✅ | Statistical functions |
pandas | ✅ | Working with heterogeneous tabular data |
openpyxl | ✅ | Reading ONS datasets from .xlsx (Excel) files |
xlrd | ✅ | Reading ONS datasets from .xls (Excel) files |
jupyterlab | ✅ | Running code from Jupyter notebooks |
matplotlib | ❌ | Visualising results (optional) |

### Running the code
Clone or download the repository:
```
git clone https://github.com/vmaguirerajpaul/mathsci-econ-contrib2.0
```
The main analysis is contained in the ```main_analysis.ipynb``` notebook. 

We do not include in this repostiory the extensive code used to visualise our results; much of that code is concerned with the detailed formatting (dimensions, fonts, colour palettes, axis specifications, etc.) of a large number of figures for reports, infographics, and presentations.

## License
Code distributed under the MIT License. See LICENSE.txt for more information.

The repository contains publicly-available datasets from the Office for National Statistics (ONS). These datasets are licensed under the Open Government Licence v 3.0.

## Authors

Vinesh Maguire Rajpaul: <vr325@cantab.ac.uk>

## Contact
AcadMathSci Policy Unit: <policyunit@AcadMathSci.org.uk>

## Acknowledgements
AcadMathSci's Policy Unit is grateful to Nigel Campbell for useful conversations that informed the framing of this work; to Dr Sophie Carr, Chris J. W. Daniels,  Prof. Cathy Hobbs, Thomas Chi-Wah Law, Prof. Ian Strachan, Prof. Colin Turner, Nathan Turner, and Simon Yun-Farmbrough for valuable input and feedback; and to the economics team at Public First for their independent review of the methodology underpinning this work. 
