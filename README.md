# Cleaning-with-Pandas
Create a script for automated data cleaning tasks using Pandas.
import pandas as pd

def clean_data(input_file, output_file):
    # Load raw data into a Pandas DataFrame
    df = pd.read_csv(input_file)

    # Perform data cleaning operations (e.g., handling missing values, removing duplicates)

    # Save the cleaned data to a new file
    df.to_csv(output_file, index=False)

# Specify input and output file paths
input_file_path = 'raw_data.csv'
output_file_path = 'cleaned_data.csv'

# Execute the data cleaning function
clean_data(input_file_path, output_file_path)
