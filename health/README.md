This folder contains the raw data used in [The Tidynomicon: A Brief Introduction to R for Python Programmers](https://github.com/gvwilson/tidynomicon). This README is modelled on <https://github.com/the-pudding/data/blob/master/pockets/README.md>, which was created for an article in The Pudding titled [Women's Pockets Are Inferior](https://pudding.cool/2018/08/pockets/), and describes each of the data files. See the README in the `tidy/` directory for a description of the table format for each tidied dataset.

## Infants born to women with HIV receiving an HIV test within two months of birth, 2009-2017

- Infant_HIV_Testing_2017.xlsx
  - **What is this?**: Excel spreadsheet with summarized data.
  - **Source(s)**: UNICEF, <https://data.unicef.org/resources/dataset/hiv-aids-statistical-tables/>
  - **Last Modified**: July 2018 (according to website)
  - **Contact**: Greg Wilson <greg.wilson@rstudio.com>
  - **Spatial Applicability**: global
  - **Temporal Applicability**: 2009-2017
- infant_hiv.csv
  - **What is this?**: CSV export from Infant_HIV_Testing_2017.xlsx
- Notes
  - Data is not tidy: some rows are descriptive comments, others are blank separators between sections, and column headers are inconsistent.
