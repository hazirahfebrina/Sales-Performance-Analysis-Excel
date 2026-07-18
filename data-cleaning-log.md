# Data Cleaning Log

## Overview

The dataset contained several intentional data quality issues that were identified and documented before analysis.

## Data Quality Issues

| Issue | Action Taken |
|-------|--------------|
| Missing Quantity and Revenue Values | Identified and flagged for review |
| Duplicate Order IDs | Flagged using Conditional Formatting (duplicates were removed) |
| Inconsistent Category Names | Standardized using `PROPER(TRIM())` |
| Inconsistent Date Format | Standardized to `dd/mm/yyyy` |
| Numeric Formatting | Converted to a consistent number format with thousand separators |
| Outliers | Reviewed numeric values and no significant outliers were identified |

## Summary

The dashboard focuses on clean rows so business decisions are based on reviewed data. Rows that require review are still documented because they may reveal process, data entry, or order management issues
