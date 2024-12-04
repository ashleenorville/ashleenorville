
# Korea Ggumim Data Cleaning Project

This project involves cleaning a dataset containing user information from Korea Ggumim. The tasks performed include:

1. Cleaning and validating email addresses.
2. Cleaning nicknames to remove control characters while retaining common symbols.

## Files in the Project

- `raw_data.csv`: The original dataset.
- `cleaned_data.csv`: The cleaned dataset.
- `garbage_files`: Temporary files created during processing.

## Steps in the Cleaning Process

1. Validate email addresses:
    - Remove invalid emails.
    - Strip extra dots and symbols.
2. Clean nicknames:
    - Remove control characters.
    - Allow common symbols like `.`, `_`, and `-`.

## How to Run

1. Ensure all dependencies are installed:
    ```
    pip install pandas numpy
    ```
2. Run the main script:
    ```
    python clean_data.py
    ```
3. The cleaned dataset will be saved as `cleaned_data.csv`.

## Garbage Files

Temporary files generated during cleaning can be found in the `garbage_files/` directory. These can be merged or deleted after the process.

## Notes

- Ensure the input file is named `Korea-ggumim.csv` and placed in the `Datasets/` directory.
