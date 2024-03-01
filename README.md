# Data Processor

This Python script contains a class called `DataProcessor` along with a helper function `split_n_save` for processing and splitting large datasets.

## DataProcessor Class

The `DataProcessor` class is designed to process CSV files and perform the following tasks:

- **Initialization**: Initializes with a file path and sets various attributes.
- **create_df()**: Creates a DataFrame from the provided CSV file.
- **confirm_balance()**: Calculates and confirms the balance of transactions in the CSV file.
- **match_data()**: Matches data based on a specific criterion and separates matched and unmatched items.
- **update_record()**: Updates records of matched and unmatched items.
- **save_output()**: Saves matched and unmatched data to separate CSV files.

## split_n_save Function

