# Data Cleaning Log

## Overview

The dataset contained several intentional data quality issues that were identified and documented before analysis.

## Data Quality Issues

| Issue | Action Taken |
|-------|--------------|
| Missing Quantity Values | Identified and flagged for review |
| Missing Revenue Values | Identified and flagged for review |
| Duplicate Order IDs | Flagged using Conditional Formatting (duplicates were not removed) |
| Inconsistent Category Names | Standardized using `PROPER(TRIM())` |
| Inconsistent Date Format | Standardized to `dd/mm/yyyy` |
| Numeric Formatting | Converted to a consistent number format with thousand separators |
| Outliers | Reviewed numeric values and no significant outliers were identified |

## Notes

The purpose of the cleaning process was to improve data consistency while preserving the original dataset. Records with missing or invalid values were flagged instead of deleted to maintain data integrity.
