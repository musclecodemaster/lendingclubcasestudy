# Loan Default Analysis Project

> A data analysis project to understand loan default patterns and risk
> factors using historical lending data.

## Table of Contents

-   [General Info](#general-information)
-   [Technologies Used](#technologies-used)
-   [Features](#features)
-   [Conclusions](#conclusions)
-   [Acknowledgements](#acknowledgements)

## General Information

### Project Background

This project analyzes lending data to identify patterns and risk factors
associated with loan defaults. The analysis aims to help financial
institutions make better lending decisions by understanding the
characteristics of loans that are more likely to default.

### Business Problem

Financial institutions need to minimize loan defaults while maintaining
a healthy lending portfolio. This project addresses: - Identifying key
risk factors for loan defaults - Understanding the relationship between
loan characteristics and default rates - Analyzing geographical patterns
in loan performance - Evaluating the effectiveness of current loan
grading systems

### Dataset

The analysis uses a loan dataset containing 39,717 records with the
following key features: - Loan amount and interest rates - Borrower
information (employment, income, credit history) - Loan grades and
sub-grades - Geographic information - Payment history and current loan
status

## Features

-   Comprehensive data cleaning and preprocessing
-   Exploratory Data Analysis (EDA) including:
    -   Univariate analysis of loan amounts and interest rates
    -   Bivariate analysis of loan status vs. various features
    -   Correlation analysis of numerical variables
    -   Geographic analysis of default rates
-   Feature engineering including loan-to-income ratio calculation
-   Visual analysis using various plot types

## Conclusions

1.  Loan Grade Impact
    -   Higher risk grades (D-G) show significantly higher default rates
    -   Interest rates correlate strongly with assigned loan grades
2.  Default Risk Factors
    -   Borrowers with lower interest rates show lower default rates
    -   Loan amounts between \$5,500 and \$15,000 show better
        performance
    -   Only 2% of loans are above \$30,000, indicating conservative
        lending at higher amounts
3.  Interest Rate Patterns
    -   Average interest rate is around 12%
    -   Clear correlation between interest rates and default probability
    -   Grade A loans consistently have the lowest interest rates
4.  Geographical Insights
    -   Default rates vary significantly by state
    -   Geographic analysis reveals regional lending patterns

## Technologies Used

-   Python - version 3.12
-   pandas - version 2.1.1
-   numpy - version 1.24.3
-   matplotlib - version 3.8.0
-   seaborn - version 0.12.2

## Acknowledgements

-   Analysis inspired by financial risk management best practices
-   Dataset provided through lending industry standard loan data
-   Methodology based on common credit risk analysis techniques

## Contact

Created by Sujana Anche & SS Krishna - feel free to contact us!
